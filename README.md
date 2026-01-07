# Smart Loan Recovery System 💰📊

A machine learning–based system that predicts whether a defaulted loan is likely to be recovered.  
The project helps financial institutions prioritize recovery efforts, reduce operational costs, and improve decision-making.

---

## 📌 Problem Statement
Loan defaults result in significant financial losses for banks and NBFCs.  
Manually identifying which defaulted loans are worth pursuing is time-consuming and inefficient.

This project uses historical loan data to **predict loan recovery status**, enabling smarter and data-driven recovery strategies.

---

## 🎯 Project Objectives
- Predict whether a loan will be **Recovered or Not Recovered**
- Identify key factors influencing loan recovery
- Provide actionable insights for financial decision-makers

---

## 🧠 Solution Approach
1. Data Cleaning and Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training using Random Forest Classifier  
5. Model Evaluation using Accuracy, Confusion Matrix, and ROC-AUC  
6. Interpretation using Feature Importance

---

## 📊 Dataset Overview
The dataset contains borrower and loan-related attributes such as:

- Loan Amount  
- Interest Rate  
- Days Past Due  
- Collection Attempts  
- Borrower Income  
- Credit Score  
- **Recovery Status (Target Variable)**

---

## ⚙️ Machine Learning Model
### Random Forest Classifier
Chosen because:
- Handles non-linear relationships effectively
- Reduces overfitting compared to single decision trees
- Provides feature importance for business interpretation
- Works well with structured/tabular data

---

## 📈 Model Evaluation
- **Accuracy:** ~96%  
- **ROC-AUC:** High (indicates strong class separation)

Evaluation techniques used:
- Confusion Matrix
- ROC Curve
- Feature Importance Analysis

---

## 🔍 Key Insights
- **Collection Attempts** and **Days Past Due** are the strongest predictors of loan recovery
- Loans with prolonged delinquency show significantly lower recovery probability
- Higher interest rates are generally associated with lower recovery chances

These insights align with real-world financial recovery logic.

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---
