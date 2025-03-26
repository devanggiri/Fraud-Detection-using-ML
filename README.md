# Fraud Detection Using Machine Learning

## Overview
This project develops a fraud detection model for financial transactions, leveraging machine learning to identify fraudulent activity in a dataset of over 6 million records.

## Objectives
- Detect fraudulent transactions with high accuracy.
- Address class imbalance using SMOTE.
- Analyze key fraud indicators.
- Provide actionable fraud prevention insights.

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn, imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Jupyter Notebook

## Key Features
- Data cleaning and preprocessing.
- Leakage-avoidant feature engineering.
- Model training using Random Forest.
- SMOTE applied for class balance.
- Strong performance: **ROC AUC = 0.99**, **Fraud Recall ≈ 99%**.
- Feature importance analysis.

## Insights
- Fraud is prevalent in **TRANSFER** and **CASH_OUT** transactions.
- Sharp decreases in `oldbalanceOrg` indicate potential fraud.
- High-value transactions with rapid balance depletion are high risk.

## Outcome
The model provides high recall, reducing missed fraud cases and supporting strategic fraud prevention initiatives.
