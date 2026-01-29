# Credit Risk Analysis 📊💳

##  Project Overview
Credit Risk Analysis is a machine learning project designed to predict whether a customer is likely to default on a loan.  
The goal is to help financial institutions make **data-driven lending decisions** by minimizing risk while maximizing profitability.

This project uses historical customer data to analyze patterns related to income, loan amount, credit history, and repayment behavior.

---

##  Problem Statement
Financial institutions face significant losses due to loan defaults.  
Manually evaluating loan applications is time-consuming and error-prone.

**Objective:**  
Build a predictive model that classifies customers as **Low Risk** or **High Risk** based on financial and demographic features.

---

##  Key Concepts Used
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Classification Algorithms
- Model Evaluation Metrics

---

##  Technologies & Tools
- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
- **Environment:** Jupyter Notebook  

---

##  Dataset Description
The dataset contains customer-level information such as:
- Age  
- Income  
- Loan Amount  
- Credit History  
- Employment Status  
- Loan Status (Target Variable)

**Target Variable:**
- `0` → Low Risk  
- `1` → High Risk  

---

##  Workflow
1. Data Loading  
2. Data Cleaning & Handling Missing Values  
3. Exploratory Data Analysis (EDA)  
4. Feature Encoding & Scaling  
5. Model Training  
6. Model Evaluation  
7. Prediction & Insights  

---

##  Model Evaluation
Evaluation metrics used:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

The best-performing model was selected based on overall performance and risk sensitivity.

---

## Results And Insights
  - Insight: Customers with poor credit history and high loan-to-income ratios have a higher default risk
  - Insight: Feature engineering significantly improved model performance
  - Insight: Ensemble models provided better accuracy and stability

---

## Future Improvements
  - Use advanced models like XGBoost or LightGBM
  - Handle class imbalance using SMOTE
  - Deploy the model using Flask or FastAPI
  - Build an interactive dashboard for risk analysis

