# 🛡️ Fraud Detection Model

A machine learning project that detects fraudulent transactions using classification techniques. The goal is to build a robust model that minimizes false negatives (missed frauds) while keeping false positives (legitimate transactions flagged as fraud) low.

---

## 📌 Project Overview
Fraudulent financial transactions are a major concern in the digital economy.  
This project leverages **machine learning** to classify transactions as **fraudulent** or **legitimate** based on historical data.

Key steps:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering and scaling
- Model training and evaluation
- Performance comparison across multiple algorithms

---

## ⚙️ Tech Stack
- **Python** 🐍  
- **Pandas / NumPy** → Data processing  
- **Matplotlib / Seaborn** → Data visualization  
- **Scikit-learn** → Machine learning models  
- **Imbalanced-learn** → Handling class imbalance (SMOTE, under/oversampling)  

---

## 🗂️ Dataset
- Source: [Kaggle](https://www.kaggle.com)  
- Transactions: ~284,807  
- Fraud cases: 492 (~0.17%)  

---

## 🧠 Model Training
We experimented with multiple classification models:
- Logistic Regression
- Random Forest
- XGBoost
- Neural Networks (optional)

Evaluation metrics:
- Precision, Recall, F1-score
- ROC-AUC
- Confusion Matrix

---

## 📊 Results
| Model              | Precision | Recall | F1-score | 
|---------------------|-----------|--------|----------|
| Logistic Regression | 0.95      | 0.93   | 0.94     | 
| K Neighbors Classifier      | 0.97      | 0.96   | 0.97     | 
| Decision Tree classifier             | 0.98     | 0.99   | 0.99     |



---
