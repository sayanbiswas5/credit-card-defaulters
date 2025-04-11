# Credit Card Defaulters Prediction 🧾📉

This project aims to build a machine learning model that predicts whether a credit card holder will default on their payment in the next month. The goal is to assist financial institutions in identifying high-risk customers early and reducing credit losses.

## 📌 Project Overview

Credit card default prediction is a classification problem where the objective is to label each user as either **default (1)** or **not default (0)**. The dataset used includes various features such as payment history, credit limit, past bill amounts, and payment amounts.

## 📁 Dataset

- **Size:** 30,000 records  
- **Features:**
  - Demographics: `LIMIT_BAL`, `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`
  - Payment History: `PAY_0` to `PAY_6`
  - Bill Amounts: `BILL_AMT1` to `BILL_AMT6`
  - Payment Amounts: `PAY_AMT1` to `PAY_AMT6`

## 🛠️ Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 ML Models Used

- Logistic Regression
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)

## 🧪 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Curve
