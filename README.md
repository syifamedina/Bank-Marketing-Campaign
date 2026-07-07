# 🏦 Bank Marketing Campaign – Term Deposit Subscription Prediction

Machine Learning classification project to predict whether a customer will subscribe to a bank term deposit based on demographic information and previous marketing campaign history.

---

## 📌 Project Overview

Banks often spend significant resources contacting customers through telemarketing campaigns. However, many calls result in no subscription.

This project develops a machine learning model to identify customers who are more likely to subscribe, allowing the marketing team to prioritize high-potential customers and improve campaign efficiency.

---

## 🎯 Business Problem

- Reduce unnecessary marketing calls
- Improve campaign conversion rate
- Help prioritize customers with higher subscription probability

Target Variable:

- **deposit**
  - yes
  - no

---

## 📊 Dataset

- **Dataset:** Bank Marketing Dataset
- **Rows:** 7,813
- **Features:** 11
- **Target:** deposit

Main Features:

- age
- job
- balance
- housing
- loan
- campaign
- pdays
- poutcome

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- GridSearchCV
- Matplotlib

---

## ⚙️ Machine Learning Workflow

1. Data Cleaning
2. Feature Engineering
3. Encoding & Scaling
4. Model Training
5. Hyperparameter Tuning
6. Model Evaluation
7. Business Recommendation

---

## 🤖 Models Evaluated

- Logistic Regression
- Random Forest
- XGBoost
- CatBoost

Hyperparameter optimization was performed using **GridSearchCV**.

---

## 📈 Evaluation Metrics

Primary Metric

- Recall

Supporting Metrics

- F1 Score
- ROC AUC

Business priority focused on minimizing False Negatives to avoid missing potential subscribers.

---

## 📂 Repository Structure

```
.
├── data
├── models
├── notebooks
├── presentation
├── src
├── README.md
└── requirements.txt
```

---

## 📌 Results

The final XGBoost model demonstrated the best overall performance for identifying potential subscribers.

The model can help marketing teams:

- Prioritize high-potential customers
- Reduce unnecessary outbound calls
- Improve campaign efficiency

---

## 🚀 Future Improvements

- Deploy as a prediction API using FastAPI
- Build an interactive dashboard with Streamlit
- Add SHAP explainability
- Monitor model performance over time

---

## 👩‍💻 Author

**Medina Assyifa**

AI Engineer Portfolio

GitHub:
https://github.com/syifamedina
