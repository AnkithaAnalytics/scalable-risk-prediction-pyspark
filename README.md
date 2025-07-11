# Scalable Risk Prediction System for Financial Transactions using PySpark & Machine Learning

This project uses **PySpark** and **Machine Learning** to classify high-risk transactions from a large-scale banking dataset (over 1 million rows).

## 🚀 Project Overview

- Loads bank transaction data using PySpark
- Applies data preprocessing and feature engineering
- Builds a **Logistic Regression** pipeline
- Classifies each transaction as **high-risk (1)** or **normal (0)**
- Saves the prediction to a new CSV file

## 🧰 Tech Stack

- Google Colab
- PySpark (SparkSession, DataFrame API)
- MLlib (Logistic Regression, Pipeline)
- Pandas, Sklearn (for export & evaluation)

## 📁 Dataset Fields

- `Date`, `Domain`, `Location`, `Value`, `Transaction_count`
- `Predicted_Risk` (0 or 1 — model output)

## 📤 Output

- `full_predictions.csv` (optional) — contains model predictions for each transaction

## 💡 Use Case

This system could be used in banking environments for early fraud/risk detection, internal audits, or financial compliance checks.

---

🔗 Built by Ankitha P. | July 2025


