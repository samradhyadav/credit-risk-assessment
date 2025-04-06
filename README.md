# 💳 Credit Risk Assessment using Probability, Statistics & Machine Learning  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samradhyadav/Credit-Risk-Assessment/blob/main/CreditRiskUsingProbability%26Statistics.ipynb)
![Python](https://img.shields.io/badge/Python-3.10-yellow.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)



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
  Unlike black-box models, I emphasize **explainable patterns**. Using probability distributions, bivariate plots, and box plots, I explore the **underlying reasons** behind loan defaults — not just predictions.

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

## 📊 Exploratory Data Analysis (EDA)

- Histograms, Box Plots: Understand distributions and outliers
- Violin & Scatter Plots: Relationship between `interest rate`, `FICO scores`, `installments`, and `loan status`
- Mutual Information & Random Forest Importances: Used to identify top features

---

## 🧠 Modeling Approach

I tested and evaluated two strong classifiers:

| Model               | AUC Score |
|--------------------|-----------|
| Logistic Regression | 0.89      |
| Random Forest       | 0.89      |

### ✅ Techniques Used

- **Feature Selection**: via Random Forest importance & Mutual Information
- **Evaluation**: 
  - ROC Curve
  - AUC Score
  - **Confusion Matrix** for classification quality
  - **Cross-validation** for stable performance estimates

---

## 📌 Key Findings

- 🔺 **Higher interest rates** are significantly correlated with **loan defaults**
- 🔻 **Lower FICO scores** (both low and high bounds) strongly indicate a higher risk of default
- 🧾 Features like `recoveries` and `collection_recovery_fee` are skewed and strongly associated with defaulted loans
- ➖ `Installment` amount is a weak predictor of default
- 📊 Mutual Information & Random Forest consistently rank `int_rate`, `fico_range_low`, `recoveries` as top features

---

## 🧮 How Probability, Statistics & ML Worked Together

- **Probability**: Helped estimate event likelihoods (default vs non-default) from historical data patterns
- **Statistics**: Used for understanding distributions (mean, median, skewness, outliers) and validating assumptions
- **ML Models**: Took these insights to **learn complex patterns**, provide **accurate predictions**, and **rank features** by importance

This synergy between explainable statistics and predictive modeling made the approach both interpretable and accurate.

---

## 📂 Files

| File / Folder | Description |
|---------------|-------------|
| `CreditRiskUsingProbability&Statistics.ipynb` | Full notebook with EDA, modeling, and evaluation |
| `README.md` | Project documentation |
| `LICENSE` | Open-source license (MIT recommended) |
| `requirements.txt` | List of required Python packages |
| `dataset` | Contains data and data source link |


---

## 📚 Dataset Used

- [Give Me Some Credit – Kaggle Competition](https://www.kaggle.com/competitions/GiveMeSomeCredit/data)

---

## ⚙️ Tech Stack

- 🐍 Python 3
- 📊 Pandas, NumPy, Matplotlib, Seaborn
- 🔍 Scikit-learn
- 🚀 Google Colab (for interactive development)

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
💼 [LinkedIn](https://www.linkedin.com/in/samradh-singh-yadav/)  
📌 Star this repo if you like it!

---

> _"Data beats emotions." — Sean Rad_

---

## 📄 License

This project is licensed under the terms of the [MIT License](LICENSE).
