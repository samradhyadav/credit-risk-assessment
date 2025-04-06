# 💳 Credit Risk Assessment using Probability, Statistics & Machine Learning

Welcome to my deep dive into **Credit Risk Assessment** using real-world data!  
This project combines **Probability & Statistics** with **Machine Learning** to predict the likelihood of loan defaults, empowering better financial decisions and risk management.

---

## 📁 Project Overview

**Goal**:  
Predict whether a loan will default based on historical data using statistical insights and ML models.

---

## 🔍 Exploratory Data Analysis (EDA)

The journey begins with data exploration and visualization:

- 📊 **Histograms & Box Plots** for key features like `interest rate`, `FICO score`, `installments`, etc.
- 📉 **Bivariate Analysis** using scatter and violin plots to discover patterns by `loan status`
- 🔎 **Feature Distribution Observations** (skewness, outliers, trends)

---

## 🧠 Modeling

We tested and evaluated two strong classifiers:

| Model               | AUC Score |
|--------------------|-----------|
| Logistic Regression | 0.89      |
| Random Forest       | 0.89      |

### ✅ Key Techniques:
- Feature selection via **Random Forest importance** and **Mutual Information**
- Model evaluation using **ROC Curves**, **Confusion Matrix**, and **Accuracy**

---

## 📌 Key Findings

- Higher **interest rates** and **lower FICO scores** significantly correlate with **loan defaults**
- Features like `recoveries` and `collection_recovery_fee` are heavily right-skewed and strong post-default indicators
- `Installment` is a weak predictor for defaults
- Mutual Information and Random Forest both confirm `int_rate`, `fico_range_low`, and `recoveries` as top features

---

## ⚙️ Tech Stack

- 🐍 Python 3
- 📊 Pandas, NumPy, Matplotlib, Seaborn
- 🔍 Scikit-learn
- 🚀 Google Colab (for interactive development)

---

## 📂 Files

| File | Description |
|------|-------------|
| `CreditRiskUsingProbability&Statistics` | Full notebook with EDA, modeling, and evaluation |
| `README.md` | You're here! |
| `dataset` | Dataset File link attached |


---

## 🧠 Inspired By

The need to quantify creditworthiness using data-driven techniques rather than gut feeling or rigid rules.

---

## 🚀 Future Work

- Hyperparameter tuning with GridSearchCV
- Ensemble techniques (e.g. XGBoost, LightGBM)
- Handling class imbalance (SMOTE)
- Deployment via Flask or Streamlit

---

## 📬 Connect with Me

📧 [reach.samradhyadav@gmail.com]  
💼 [LinkedIn]([https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/samradh-singh-yadav/))  
📌 Star this repo if you like it!

---

> _"Data beats emotions." — Sean Rad_

