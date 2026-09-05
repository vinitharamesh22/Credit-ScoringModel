# Credit Scoring Model

An AI/ML-based credit scoring system that analyzes financial and behavioral attributes to assess the likelihood of loan default. The project compares multiple machine learning algorithms and evaluates their performance using standard classification metrics.

## 🎯 Project Overview

Credit scoring plays an important role in assessing an applicant's financial risk. This project demonstrates how machine learning can be used to predict whether an applicant is likely to default based on financial and behavioral characteristics.

The project uses synthetically generated financial data, making it fully reproducible without exposing real customer information.

## ✨ Features

- Synthetic financial applicant data generation
- Credit default prediction
- Feature engineering
- Multiple machine learning model comparison
- Automated model evaluation
- Reproducible experiments
- Performance metrics exported to CSV

## 🤖 Machine Learning Models

The project compares three classification algorithms:

1. Logistic Regression
2. Decision Tree
3. Random Forest

The models use preprocessing pipelines with:

- Missing-value imputation
- Feature scaling
- One-hot encoding for categorical features

## 📊 Features Used

### Numerical Features

- Annual income
- Debt amount
- Credit utilization
- Payment delays in the last 12 months
- Credit history years
- Number of open accounts

### Categorical Features

- Employment status
- Home ownership

### Engineered Features

- Debt-to-income ratio
- Income per account

## 📈 Model Evaluation

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

The resulting metrics are saved in:

`outputs/model-metrics.csv`

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- HTML/CSS
- Flask / Python Web Application
- Pytest

## 📁 Project Structure

```text
credit-scoring-model/
│
├── static/
├── templates/
├── outputs/
│   └── model-metrics.csv
│
├── app.py
├── credit_scoring.py
├── pyproject.toml
├── requirements.txt
├── test_app.py
├── test_credit_scoring.py
└── README.md
