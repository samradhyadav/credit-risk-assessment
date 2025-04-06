# 💳 Credit Risk Assessment using Probability, Statistics & Machine Learning

Welcome to my deep dive into **Credit Risk Assessment** using real-world data!  
This project combines **Probability & Statistics** with **Machine Learning** to predict the likelihood of loan defaults, empowering better financial decisions and risk management.

---

## 🎯 Project Idea & Motivation

In today's digital financial landscape, lending institutions are increasingly relying on **data-driven strategies** to evaluate the creditworthiness of borrowers. Traditional credit scoring methods, while useful, often fall short in capturing the nuanced patterns hidden in large-scale financial data.

This project was born out of the idea to **leverage probability and statistics**, along with **machine learning**, to build a more robust and interpretable system for **Credit Risk Assessment**. 

---

### 💡 Why This Project?

- 💳 **Real-World Relevance**:  
  Credit risk evaluation lies at the heart of banking and lending institutions. With the rise in peer-to-peer lending platforms like LendingClub, there's a massive volume of structured loan data available to analyze and improve loan decisioning systems.

- 📈 **Data Science Meets Finance**:  
  This project was a perfect opportunity to apply **statistical analysis**, **feature engineering**, and **modeling** techniques to a domain that affects millions—finance and lending.

- 🔍 **Explainability and Insight**:  
  Unlike black-box models, this project emphasizes explainable patterns. Using probability distributions, bivariate plots, and box plots, I explored the **underlying reasons** behind loan defaults — not just predictions.

- 🎓 **Learning Goals**:
    - Apply statistical thinking to real-world data  
    - Visualize trends that affect loan outcomes  
    - Understand which variables truly matter in predicting defaults  
    - Practice end-to-end machine learning workflow in a business-critical domain

---

## 📁 Project Overview

**Goal**:  
Predict whether a loan will default based on historical data using statistical insights and ML models.

---

## 📊 Dataset Used

📦 [Give Me Some Credit — Kaggle Competition Dataset](https://www.kaggle.com/competitions/GiveMeSomeCredit/data)  
This dataset provides anonymized features about customers’ financial behavior, including delinquency records, revolving credit balance, and monthly income.

---

## 🔍 Exploratory Data Analysis (EDA)

The journey begins with data exploration and visualization:

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
- Model evaluation using:
  - **K-Fold Cross-Validation** (5-fold)
  - **ROC Curves** for performance visualization
  - **Confusion Matrix** for classification accuracy breakdown
  - **Accuracy, Precision, Recall, and AUC** metrics

---

## 📌 Key Findings

- **High Interest Rates = High Risk**: Borrowers with higher interest rates were more likely to default, as seen in box plots, violin plots, and confirmed by feature importance scores.  
- **FICO Scores are Vital**: Both the low and high ranges of FICO scores showed strong separation between defaulted and non-defaulted loans. Lower FICO ranges were closely tied to increased default probability.
- **Recoveries and Collection Fees Spike After Default**: These two features are not predictive *before* default but show sharp increases *after* default, highlighting their use in post-default risk profiling.
- **Weak Features Detected**: Some features like `installment` didn’t provide clear separation or predictive power between default and non-default cases.
- **Mutual Information & Random Forest Alignment**: Both selection techniques pointed to `int_rate`, `recoveries`, and `fico_range_low` as dominant predictors, reinforcing confidence in model interpretability.
- **Loan Default is Rare but Costly**: Class imbalance in the dataset shows that while most loans do not default, those that do can cause significant financial loss, making accurate prediction critical.

---

## 📊 Role of Probability, Statistics & Machine Learning

- 📈 **Probability & Statistics**:
    - Helped identify the **distribution of features** using histograms, box plots, and violin plots.
    - Detected **outliers and skewness**, crucial for preprocessing and normalization.
    - Allowed **correlation analysis** to understand linear relationships (e.g., FICO vs Interest Rate).
    - Informed **feature selection** by evaluating variable spread, variance, and density across categories.

- 📎 **Mutual Information (Statistics)**:
    - Measured **non-linear dependencies** between features and target variable.
    - Helped rank features that hold the **most useful information** about the likelihood of default.

- 🤖 **Machine Learning**:
    - Enabled **pattern recognition** through supervised models like Logistic Regression and Random Forest.
    - Offered **probability-based predictions** using Logistic Regression's sigmoid outputs.
    - Provided **interpretability** via Random Forest feature importances.
    - Evaluated using metrics like **AUC-ROC**, **accuracy**, and **confusion matrix** to validate performance.

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
| `dataset` | Dataset with Kaggle source link |

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

📧 reach.samradhyadav@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/samradh-singh-yadav/)  
📌 Star this repo if you like it!

---

> _"Data beats emotions." — Sean Rad_
