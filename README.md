# 🧠 Mental Health Factors — Decision Tree Classification

**🎓 Academic Project | Bachelor's Degree in Information Systems — Centro Universitário Fundação Santo André (FSA)**

![Academic Project](https://img.shields.io/badge/Type-Academic%20Project-6f42c1) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

---

## 📌 Project Overview

This academic machine learning exercise explores the use of a **Decision Tree classifier** to categorize records based on mental health and lifestyle factors from a public dataset. The main purpose is to practice preprocessing, target construction, supervised learning and model evaluation.

**Important:** the target used in this exercise is derived from a dataset score; the model does **not** diagnose depression or replace professional mental health assessment.

---

## 🎯 Objectives

- Prepare a dataset for a supervised classification experiment.
- Explore relationships between lifestyle indicators and the defined target.
- Train a decision tree and understand the basics of classification.
- Evaluate limitations before interpreting any predictions.

## 📚 Dataset

**Source:** [Anxiety and Depression Mental Health Factors — Kaggle](https://www.kaggle.com/datasets/ak0212/anxiety-and-depression-mental-health-factors?resource=download).

Variables documented in the original project:

- `Sleep_Hours`
- `Physical_Activity_Hrs`
- `Social_Support_Score`
- `Stress_Level`
- `Self_Esteem_Score`
- `Depression_Score`

## ⚙️ Methodology

According to the original project documentation:

1. Select the input features and remove rows with missing values.
2. Build a binary **educational target** called `depressao`, using `Depression_Score >= 10` as class `1` and lower scores as class `0`.
3. Remove `Depression_Score` from the input features to avoid using the same column directly as a predictor.
4. Split the data into **80% training / 20% testing** (`test_size=0.2`).
5. Train a `DecisionTreeClassifier` using **scikit-learn**.

The threshold above is a **project-defined labeling rule**, not a clinical diagnostic cutoff.

## 🛠️ Technologies

- **Python** — programming language.
- **Pandas** — dataset manipulation.
- **scikit-learn** — decision tree classification.

## 📁 Repository Structure

```text
ml-anxiety-depression-analysis/
├── data/
│   └── raw/   # Source data
├── src/       # Machine learning code
└── README.md
```

## 📈 Results & Limitations

The previous README contained placeholders for accuracy and a sample prediction. They have been removed because **a validated metric and corresponding run output were not provided in the repository documentation**. Quantitative results should be added only after reproducing the experiment and recording its evaluation.

This is a learning exercise, not a validated screening tool. A score-derived target does not establish a medical diagnosis, and the generalizability of predictions has not been demonstrated here.

## 🎓 Academic Context

Developed as an **academic project during the Information Systems bachelor's degree at Fundação Santo André (FSA)** to apply introductory machine learning concepts to a public dataset.
