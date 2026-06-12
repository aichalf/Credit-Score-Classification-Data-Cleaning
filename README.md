# 💳 Credit Score Classification — Data Cleaning & Preprocessing

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![pandas](https://img.shields.io/badge/pandas-Data%20Wrangling-blue) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> Professional data cleaning pipeline on a credit score dataset — handling missing values, outliers, encoding, and feature normalization for downstream ML.

## 📌 Overview

This project demonstrates industry-standard data preparation techniques applied to a real-world credit score classification dataset, transforming messy raw data into a clean, analysis-ready format.

## 🔍 Data Quality Issues Addressed

| Issue | Technique Applied |
|---|---|
| Missing values | Median imputation (numerical), mode (categorical) |
| Outliers | IQR-based detection and treatment |
| Inconsistent types | Type casting and format standardization |
| Categorical encoding | Label encoding + one-hot encoding |
| Feature scaling | StandardScaler / MinMaxScaler |
| Class imbalance | Analysis and documentation |

## 📊 Dataset Features
`annual_income` · `payment_behavior` · `credit_history_age` · `num_loans` · `credit_utilization_ratio` · `outstanding_debt` · `monthly_balance`

## 🛠️ Tech Stack
`Python` · `pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `scikit-learn`

## 💼 Business Applications
- Credit risk modeling and probability of default (PD) estimation
- Banking KYC and customer scoring pipelines
- Financial services data engineering

## 🚀 Run Locally
```bash
git clone https://github.com/aichalf/Credit-Score-Classification-Data-Cleaning
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Copie_de_Dataset_2_CSI4142_A2.ipynb
```

## 👩‍💻 Author
**Aicha Lfakir** · [LinkedIn](https://linkedin.com/in/aicha-lfakir) · [GitHub](https://github.com/aichalf)
