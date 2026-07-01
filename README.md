# 🎮 Previsão de Vendas de Jogos do PlayStation com Machine Learning

## 📌 Objetivo

Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever as vendas globais de jogos do PlayStation antes do seu lançamento, utilizando informações disponíveis durante o desenvolvimento do jogo.

O projeto segue todo o ciclo de um projeto de Ciência de Dados, desde a análise exploratória até a construção, validação, interpretação e otimização dos modelos preditivos.

---

# 📂 Base de Dados

A base utilizada contém informações de jogos lançados para PlayStation, incluindo:

* Nome do jogo
* Plataforma
* Gênero
* Desenvolvedora
* Publicadora
* Data de lançamento
* Nota da crítica
* Nota dos usuários
* Quantidade de avaliações
* Número de jogadores
* Classificação indicativa
* Vendas globais

---

# 🎯 Problema de Negócio

Empresas desenvolvedoras de jogos precisam estimar o potencial de vendas de um título antes do lançamento para tomar decisões relacionadas a:

* Investimentos em marketing;
* Planejamento financeiro;
* Distribuição física e digital;
* Definição de metas comerciais;
* Avaliação de risco do projeto.

O objetivo deste projeto é utilizar Machine Learning para apoiar essas decisões.

---

# ❓ Pergunta de Negócio

É possível prever as vendas globais de um jogo utilizando apenas suas características antes do lançamento?

---

# 🛠 Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* SHAP
* Joblib

---

# 📊 Etapas do Projeto

## 1. Coleta dos Dados

Foi utilizada uma base contendo informações de jogos lançados para PlayStation.

---

## 2. Análise Exploratória

Durante esta etapa foram realizadas análises como:

* Estrutura da base
* Tipos das variáveis
* Estatísticas descritivas
* Valores ausentes
* Tratamento de datas
* Remoção de duplicatas
* Matriz de correlação
* Distribuição das vendas
* Distribuição dos jogos por plataforma
* Distribuição por gênero

Essa etapa permitiu compreender o comportamento dos dados antes da modelagem.

---

## 3. Engenharia de Atributos

Foram criadas variáveis capazes de melhorar o desempenho do modelo.

Também foi realizado o tratamento das variáveis categóricas através de Pipeline de Pré-processamento.

---

## 4. Controle de Vazamento de Dados

Uma das principais preocupações do projeto foi evitar Data Leakage.

Variáveis que continham informações indisponíveis antes do lançamento do jogo foram removidas para garantir que o modelo representasse um cenário real de negócio.

---

# 🤖 Modelos Avaliados

Foram treinados e comparados diversos algoritmos de regressão:

* Regressão Linear
* Random Forest
* Extra Trees
* Gradient Boosting
* XGBoost

Cada modelo foi avaliado utilizando métricas de desempenho.

---

# 📈 Métricas Utilizadas

Os modelos foram comparados utilizando:

* R² (Coeficiente de Determinação)
* MAE (Erro Absoluto Médio)
* RMSE (Raiz do Erro Quadrático Médio)

Além disso foi utilizada:

* Validação Cruzada (Cross Validation)
* GridSearchCV
* Curva de Aprendizado

para verificar estabilidade e capacidade de generalização.

---

# 🔍 Interpretabilidade

Para entender como o modelo toma decisões foram utilizadas duas abordagens:

## Importância das Variáveis

Identificação das características mais relevantes para previsão das vendas.

## SHAP

Explicação individual das previsões permitindo interpretar a influência de cada variável em cada jogo.

---

# 📊 Visualizações

O projeto apresenta diversas visualizações, entre elas:

* Comparação dos Modelos (R²)
* Predito × Real
* Top 10 Variáveis Mais Importantes
* Distribuição das Vendas
* Jogos por Plataforma
* Top Gêneros
* Matriz de Correlação
* Curva de Aprendizado
* Análise de Resíduos

Esses gráficos facilitam a interpretação dos resultados obtidos.

---

# 📈 Resultados

Após comparar todos os algoritmos, o melhor modelo foi selecionado com base em seu desempenho nas métricas de avaliação.

O projeto também inclui:

* Validação Cruzada
* Ajuste de hiperparâmetros com GridSearchCV
* Diagnóstico de Overfitting
* Avaliação dos maiores erros
* Interpretação das previsões utilizando SHAP

Essas etapas aumentam a confiabilidade do modelo desenvolvido.

---

# 🚀 Aplicação

Ao final foi construída uma função capaz de prever as vendas de um novo jogo utilizando apenas suas características antes do lançamento.

Além disso, o modelo treinado foi salvo para reutilização futura.

# 📌 Conclusão

Este projeto demonstra a aplicação completa de um fluxo profissional de Ciência de Dados para previsão de vendas de jogos eletrônicos.

Desde a preparação dos dados até a interpretação dos resultados, todas as etapas foram conduzidas buscando construir um modelo robusto, interpretável e aplicável em um contexto real de negócio.

O resultado final evidencia como técnicas de Machine Learning podem auxiliar empresas do setor de games na tomada de decisões estratégicas antes do lançamento de novos produtos.
