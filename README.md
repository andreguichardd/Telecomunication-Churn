# Customer Churn Prediction — Telco

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andreguichardd/Telecomunication-Churn/blob/main/churn_prediction.ipynb)

**End-to-end ML pipeline predicting customer churn for a telecommunications company.**

---

## Problem

Telecom companies lose significant revenue to customer churn. The goal of this project is to predict which customers are at high risk of churning, allowing retention teams to intervene before they leave.

---

## Dataset

- 7,000+ customer records
- Features: tenure, contract type, services subscribed, billing information, payment method, support interactions

---

## Approach

- **Exploratory Data Analysis** — understanding churn drivers across customer segments
- **Feature Engineering** — tenure segmentation, service scoring, contract type encoding
- **Model** — XGBoost classifier
- **Evaluation** — AUC-ROC for model performance, SHAP values for feature-level explainability

---

## Results

- Identified key churn drivers: contract type, tenure, and service bundling
- Model evaluated with AUC-ROC and validated through SHAP analysis to ensure predictions are explainable to business stakeholders

---

## Tech Stack

```
Python    Pandas · NumPy · Scikit-learn · XGBoost · SHAP · Matplotlib · Seaborn
```

---

## Project Structure

```
├── churn_prediction.ipynb   # Full pipeline: EDA, feature engineering, modelling, evaluation
└── README.md
```
