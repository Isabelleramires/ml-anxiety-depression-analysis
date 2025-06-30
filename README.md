# 🧠 Previsão de Depressão com Árvore de Decisão: Análise de Fatores de Saúde Mental

## ✨ Visão Geral do Projeto

Este projeto de Machine Learning utiliza uma **Árvore de Decisão** para prever a presença de depressão com base em fatores de saúde mental e hábitos de vida. O objetivo é demonstrar a aplicação de algoritmos de classificação para auxiliar na detecção precoce.

## 📚 Fonte de Dados

O dataset "Anxiety and Depression Mental Health Factors" foi obtido do **Kaggle**.

Link para o dataset original:
[https://www.kaggle.com/datasets/ak0212/anxiety-and-depression-mental-health-factors?resource=download](https://www.kaggle.com/datasets/ak0212/anxiety-and-depression-mental-health-factors?resource=download)

Variáveis principais utilizadas: `Sleep_Hours`, `Physical_Activity_Hrs`, `Social_Support_Score`, `Stress_Level`, `Self_Esteem_Score`, `Depression_Score`.

## 🧹 Pré-processamento dos Dados

1.  **Seleção de Features:** Colunas relevantes foram selecionadas.
2.  **Tratamento de Valores Ausentes:** Linhas com `NaN` foram removidas.
3.  **Criação da Variável Alvo (`depressao`):** `Depression_Score >= 10` resultou em `1` (depressão), caso contrário `0`.
4.  **Remoção da Coluna Original:** `Depression_Score` foi removida.

## 🚀 Metodologia

1.  **Definição de Features (X) e Target (y):** Variáveis independentes e dependente foram definidas.
2.  **Divisão Treino/Teste:** Dados divididos em 80% treino e 20% teste (`test_size=0.2`).
3.  **Treinamento do Modelo:** `DecisionTreeClassifier` foi treinado com os dados de treino.

## ✅ Avaliação do Modelo

**Acurácia do Modelo:** [Sua acurácia aqui, ex: 85.50%]%

## 🎯 Exemplo de Predição

Exemplo de predição com dados de entrada: `[6.0, 0.5, 2, 7, 5]`.
**Resultado:** [Seu resultado aqui, ex: "Com depressão"]

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* Scikit-learn
