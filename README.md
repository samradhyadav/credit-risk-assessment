# 💳 Credit Risk Assessment using Probability, Statistics & Machine Learning

Welcome to my deep dive into **Credit Risk Assessment** using real-world data!  
This project combines **Probability & Statistics** with **Machine Learning** to predict the likelihood of loan defaults, empowering better financial decisions and risk management.

---

## 🎯 Project Idea & Motivation

In today's digital financial landscape, lending institutions are increasingly relying on **data-driven strategies** to evaluate the creditworthiness of borrowers. Traditional credit scoring methods, while useful, often fall short in capturing the nuanced patterns hidden in large-scale financial data.

This project was born out of my idea to **leverage probability and statistics**, along with **machine learning**, to build a more robust and interpretable system for **Credit Risk Assessment**. 

---

### 💡 Why This Project?

- 💳 **Real-World Relevance**:  
  Credit risk evaluation lies at the heart of banking and lending institutions. With the rise in peer-to-peer lending platforms like LendingClub, there's a massive volume of structured loan data available to analyze and improve loan decisioning systems.

- 📈 **Data Science Meets Finance**:  
  This project was a perfect opportunity for me to apply **statistical analysis**, **feature engineering**, and **modeling** techniques to a domain that affects millions—finance and lending.

- 🔍 **Explainability and Insight**:  
  Unlike black-box models, I emphasized explainable patterns. Using probability distributions, bivariate plots, and box plots, I explored the **underlying reasons** behind loan defaults — not just predictions.

- 🎓 **Learning Goals**:
    - Apply statistical thinking to real-world data  
    - Visualize trends that affect loan outcomes  
    - Understand which variables truly matter in predicting defaults  
    - Practice end-to-end machine learning workflow in a business-critical domain

---

This project isn’t just about building a model — it’s about uncovering **what the data says about risk**, and translating those insights into **actionable decisions** for safer lending practices.

---

## 📁 Project Overview

**Goal**:  
Predict whether a loan will default based on historical data using statistical insights and ML models.

---

## 🔍 Exploratory Data Analysis (EDA)

My journey begins with data exploration and visualization:

- 📊 **Histograms & Box Plots** for key features like `interest rate`, `FICO score`, `installments`, etc.
- 📉 **Bivariate Analysis** using scatter and violin plots to discover patterns by `loan status`
- 🔎 **Feature Distribution Observations** (skewness, outliers, trends)

---

## 🧠 Modeling

I tested and evaluated two strong classifiers:

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
| `CreditRiskUsingProbability&Statistics.ipynb` | Full notebook with EDA, modeling, and evaluation |
| `README.md` | You're here! |
| `dataset/file.csv` | Dataset file with a link to the data source |

---

## 🚀 Future Work

- Hyperparameter tuning with GridSearchCV
- Ensemble techniques (e.g. XGBoost, LightGBM)
- Handling class imbalance (SMOTE)
- Deployment via Flask or Streamlit

---

## 📬 Connect with Me

📧 reach.samradhyadav@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/samradh-singh-yadav/)  
📌 Star this repo if you like it!

---

> _"Data beats emotions." — Sean Rad_
