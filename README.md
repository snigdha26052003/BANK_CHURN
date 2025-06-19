# 🏦 Bank Customer Churn Prediction

This project predicts whether a bank customer is likely to churn (leave the bank) using machine learning, and provides business insights based on demographic and behavioral patterns.

---

## 📌 Problem Statement

Customer churn impacts profitability. The objective is to build a classification model that predicts churn and identify key drivers contributing to it.

---

## 📊 Dataset Description

The dataset includes the following features:

- CustomerID, Geography, Gender
- Age, Tenure, Balance, EstimatedSalary
- NumOfProducts, IsActiveMember
- Exited (Target: 1 = Churned, 0 = Retained)

---

## 🔧 Tools & Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)

---

## 🔍 Workflow

1. Data Cleaning & Encoding
2. Exploratory Data Analysis (EDA)
3. Handling Class Imbalance with SMOTE
4. Model Building & Evaluation
5. Feature Selection 
6. Business Insights Generation

---

## ✅ Model Performance (XGBoost)

- Accuracy: ~87%

---

## 📈 Business Insights

- Churn is lowest among customers aged 30–40 and increases with age.
- Customers aged 50–60 show the highest churn risk.
- High-balance customers tend to churn more.
- Customers with exactly 2 products have the lowest churn rate.
- Inactive members churn more than active ones.
- France and Germany have the largest customer bases.

---
## 🧠 Future Improvements

- Build a dashboard using Streamlit or Flask
- Deploy the model as an API

---

## 🙋‍♀️ Author

**Snigdha Saha**  
MSc Statistics | Aspiring Data Scientist  
📫 [LinkedIn](www.linkedin.com/in/snigdha-saha-287b60259) 
