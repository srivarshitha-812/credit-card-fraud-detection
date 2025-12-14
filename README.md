# Credit Card Fraud Detection

## 📌 Overview
This project implements a machine learning–based fraud detection system to identify fraudulent credit card transactions from highly imbalanced data.

## 🧠 Problem Statement
Credit card fraud datasets are extremely imbalanced, where fraudulent transactions represent a very small percentage of total transactions. The goal is to maximize fraud detection while minimizing false negatives.

## 📊 Dataset
- Transactions: 284,807
- Fraud cases: ~0.17%
- Source: Kaggle Credit Card Fraud Dataset

## ⚙️ Approach
- Data preprocessing and feature scaling
- Handling class imbalance using SMOTE
- Model training using:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Evaluation using business-critical metrics (Recall, Precision)

## 📈 Key Focus
- Prioritized **Recall** to minimize missed fraud cases
- Balanced trade-off between false positives and false negatives

## 🛠️ Tech Stack
- Python
- Scikit-learn
- XGBoost
- SMOTE

## 🚀 Results
The optimized model achieved improved recall, making it suitable for real-world fraud detection scenarios.

## 📂 Project Structure
- `notebooks/` – Exploratory analysis and model experimentation
- `src/` – Training and evaluation scripts

## 📌 Use Case
This system can assist financial institutions in reducing fraud losses and improving transaction security.
