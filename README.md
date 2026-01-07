# Smart Loan Recovery System

## 📌 Problem Statement
Loan defaults cause significant financial losses for banks.  
This project predicts whether a loan is likely to be recovered using historical borrower and loan data.

## 🎯 Objective
- Predict **Recovery Status** (Recovered / Not Recovered)
- Help financial institutions prioritize recovery efforts

## 🧠 Approach
- Data Cleaning & EDA
- Feature Engineering
- Random Forest Classification
- Model Evaluation using Accuracy, ROC-AUC, Confusion Matrix

## 📊 Dataset Features
- Loan Amount
- Interest Rate
- Days Past Due
- Collection Attempts
- Borrower Income
- Credit Score
- Recovery Status (Target)

## ⚙️ Algorithm Used
**Random Forest Classifier**
- Handles non-linearity
- Robust to outliers
- Provides feature importance

## 📈 Model Performance
- Accuracy: ~96%
- ROC-AUC: High (shows strong class separation)

## 🔍 Key Insights
- Collection Attempts and Days Past Due were the most important features
- Higher interest rates correlated with lower recovery probability

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🚀 Future Improvements
- Handle class imbalance using SMOTE
- Add real-time prediction API
- Compare with XGBoost / Logistic Regression

## 👤 Author
Krish Agarwal
