# Credit Scoring Model

An AI/ML-powered credit scoring web application that analyzes financial and behavioral information to estimate an applicant's probability of credit default.

## 🎯 Project Overview

Credit scoring is an important part of financial risk assessment. This project demonstrates how machine learning can be used to analyze applicant information and identify potential credit default risk.

The system generates synthetic financial data, trains multiple machine learning models, compares their performance, and provides an interactive web interface for making predictions.

> **Note:** The project uses synthetic data and is intended for educational and demonstration purposes.

## ✨ Features

- Credit default risk prediction
- Interactive web interface
- Multiple machine learning models
- Synthetic financial data generation
- Feature engineering
- Model performance comparison
- Probability-based risk assessment
- Automated model evaluation
- API endpoints for predictions and metrics
- Input validation
- Automated tests

## 🤖 Machine Learning Models

The system compares three classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## 📊 Input Features

The model uses the following applicant information:

### Financial Features

- Annual income
- Debt amount
- Credit utilization
- Payment delays in the last 12 months
- Credit history length
- Number of open accounts

### Applicant Features

- Employment status
- Home ownership

### Engineered Features

The system additionally calculates:

- Debt-to-income ratio
- Income per account

## 🌐 Web Application

The Flask web application provides:

### Dashboard

An interactive interface for exploring the credit scoring system.

### Prediction

Users can enter applicant information and select a machine learning model to receive:

- Default probability
- Prediction result
- Risk decision
- Debt-to-income ratio

### Model Metrics

The application also provides model evaluation metrics and the sample size used for training.

## 🛠️ Technologies Used

- **Python**
- **Flask**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **HTML**
- **CSS**
- **JavaScript**
- **Pytest**

## 📁 Project Structure

```text
credit-scoring-model/
│
├── static/
│   └── Website assets
│
├── templates/
│   └── Web page templates
│
├── outputs/
│   └── model-metrics.csv
│
├── app.py
├── credit_scoring.py
├── pyproject.toml
├── requirements.txt
├── test_app.py
├── test_credit_scoring.py
├── .gitignore
└── README.md
