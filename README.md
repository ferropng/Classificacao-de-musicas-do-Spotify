# 🎧 Classificação de Músicas do Spotify

Projeto de Ciência de Dados focado na classificação de músicas como **agitadas** ou **lentas**, com base em atributos de áudio disponíveis na API do Spotify. Também foi desenvolvido um modelo de **regressão** para prever a **popularidade** das faixas.

## 🔍 Objetivo

Explorar dados de músicas do Spotify e aplicar algoritmos de Machine Learning para:

- Classificar músicas como agitadas ou lentas
- Prever a popularidade de uma música
- Avaliar diferentes modelos e técnicas de pré-processamento

## 🧠 Técnicas Utilizadas

- Análise exploratória de dados (EDA)
- Criação de variável alvo com base em `valence`
- Pré-processamento de dados (normalização, codificação)
- Modelos de classificação:
  - Regressão Logística
  - KNN
  - Random Forest (com e sem GridSearch)
- Regressão para prever popularidade
- Avaliação com métricas: Accuracy, ROC AUC, MAE, RMSE, R²

## 📊 Principais Resultados

- O modelo de **Random Forest otimizado com GridSearch** obteve o melhor desempenho na tarefa de classificação.
- O modelo de **Regressão Linear** apresentou resultados satisfatórios na previsão de popularidade, com bom ajuste conforme as métricas avaliadas.

## 💾 Dataset

- Dataset utilizado: [Spotify Tracks Dataset - Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)
