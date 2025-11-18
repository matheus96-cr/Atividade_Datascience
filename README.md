# Atividade 8: Comparação de Modelos de Regressão - Previsão de Consumo de Energia

## 🎯 Objetivo

Este projeto foi desenvolvido para a disciplina de **Data Science - Princípios e Técnicas** (Prof. Dr. Welton Dionisio) com o objetivo de comparar o desempenho de três modelos de Machine Learning em um problema de Regressão.

## 💾 Dataset

O dataset utilizado é o **Consumo de Energia Horário (PJM Load Hourly)**, que registra o consumo de Megawatts ao longo do tempo.

## 🛠️ Modelos Comparados

Foram implementados e avaliados os seguintes modelos de regressão:

1.  **Regressão Linear** (`LinearRegression`)
2.  **Random Forest Regressor** (`RandomForest`)
3.  **XGBoost Regressor** (`XGBoost`)

## 📊 Resultados (Melhor Desempenho)

| Métrica | Melhor Modelo (XGBoost) | Interpretação |
| :--- | :--- | :--- |
| **R²** | **0.7318** | Explica 73.18% da variação do consumo. |
| **MAE** | **2255.23 MW** | Erro médio de 2.255 MW por previsão. |

> O **XGBoost** demonstrou ser o mais adequado, superando os demais por capturar a natureza não-linear e cíclica dos dados de série temporal.

## 📁 Como Executar o Projeto

Para visualizar a análise completa, incluindo código, gráficos e documentação passo a passo:

1.  Baixe ou clone o repositório.
2.  Abra o arquivo **`Atividade8_Regressao.ipynb`** em um ambiente Jupyter (VS Code, JupyterLab ou Google Colab).
3.  Execute as células em ordem.

---
**Desenvolvido por:** [Nome do Membro 1, Nome do Membro 2, etc.]
