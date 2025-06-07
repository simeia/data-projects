# 🔍 Churn Prediction com CRISP-DM

Este projeto aplica a metodologia **CRISP-DM** para prever o cancelamento de clientes (churn) com base em dados de uma operadora de serviços de telecomunicação.

## 🎯 Objetivo

Antecipar o risco de churn entre pequenas e médias empresas que assinaram o pacote nos últimos 12 meses, permitindo ações proativas de retenção por parte do time de Customer Success.

## 🛠️ Etapas do Projeto

- **Business Understanding:** formulação da pergunta "Quais clientes têm maior probabilidade de cancelar nos próximos 30 dias?"
- **Data Understanding:** exploração das variáveis, análise de distribuição, valores nulos, e padrões visuais relacionados ao churn.
- **Data Preparation:** limpeza, tratamento de nulos, remoção de colunas irrelevantes, encoding e balanceamento da base.
- **Modeling:** treinamento de um modelo de classificação com **Random Forest**.
- **Evaluation:** análise da performance com métricas clássicas (acurácia, recall, f1-score), matriz de confusão e ranking das variáveis mais relevantes.
- **Deployment (simulado):** previsão de churn para novos clientes com base em características específicas.

## 🧪 Resultados

- **Acurácia:** 96%
- **F1-score (Churn):** 91%
- **Principais variáveis preditivas:** `Satisfaction Score`, `Tenure in Months`, `Monthly Charge`, `Contract Type`, entre outras.
- **Insight principal:** o nível de satisfação do cliente é o maior indicador de risco de cancelamento.

## 📁 Estrutura

- `churn_prediction.ipynb` — notebook principal com todas as etapas do projeto
- `telco.csv` — conjunto de dados original (dados sintéticos)
- `README.md` — este arquivo

## ✅ Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn
