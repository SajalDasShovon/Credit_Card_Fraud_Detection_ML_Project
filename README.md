# Credit Card Fraud Detection ML Project

This project implements a complete machine-learning pipeline for detecting fraudulent credit-card transactions under extreme class imbalance.
Using the well-known Kaggle Credit Card Fraud Dataset, we develop and evaluate multiple models, analyze class imbalance, perform interpretability with SHAP, and study threshold-dependent behavior.

***Project Highlights***  
-End-to-end ML pipeline for fraud detection  
-Handles severe class imbalance (fraud ≈ 0.17%)  

Implements:  
-Data preprocessing  
-Feature scaling  
-SMOTE oversampling  
-Undersampling  
-Class-weight balancing  

***Models included:***  
-Logistic Regression (plain & balanced)  
-Random Forest (plain & class-balanced)  
-Decision Tree  
-XGBoost  
-Multilayer Perceptron (MLP)  


***Dataset*** 
-We used the publicly available Kaggle Credit Card Fraud Dataset, containing: 284,807 transactions  
-492 fraud cases (0.172%)  
-PCA-transformed features (V1–V28), plus Time and Amount  

Dataset link:  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud  



***How to Run the Project***
1. Clone the repository  
https://github.com/SajalDasShovon/Credit_Card_Fraud_Detection_ML_Project    
cd Credit_Card_Fraud_Detection_ML_Project   

2. Install dependencies  
pip install numpy pandas scikit-learn imbalanced-learn xgboost shap tensorflow matplotlib seaborn  

3. Run the notebook  
Open Jupyter Notebook or VS Code:  
jupyter notebook credit_card_fraud_notebook_final.ipynb  

