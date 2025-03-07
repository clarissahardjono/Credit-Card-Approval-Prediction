# Credit-Card-Approval-Prediction
Predicting credit card approval using machine learning models. The project explores CART, Random Forest, and Logistic Regression models to enhance financial decision-making while ensuring fairness and mitigating bias.

## Project Overview
This project predicts credit card approval outcomes using machine learning models. The goal is to improve the efficiency of financial decision-making while ensuring fairness and mitigating bias. The dataset includes various demographic and financial features used by financial institutions to assess applicants.

## Key Features
- **Machine Learning Models**: CART (Decision Trees), Random Forest, Logistic Regression.
- **Data Preprocessing**: Handling missing values, encoding categorical features, and feature scaling.
- **Model Evaluation**: Accuracy, precision, recall, F1-score, ROC-AUC, and OSR².
- **Bias & Fairness Considerations**: Analyzing disparities in approval rates across different demographic groups.
- **Feature Engineering**: Derived features like Income_YearsEmployed, Debt_to_Income, High_CreditScore, and Age_Group.

## Project Goals
- **Enhance credit approval predictions** using machine learning.
- **Improve fairness and transparency** in financial decision-making.
- **Optimize feature selection** to identify the most impactful applicant attributes.
- **Reduce systematic bias** in credit approvals.

## Datasets
- **Credit Card Application Dataset** (UC Irvine Machine Learning Repository): Contains applicant details and approval status.

## Findings & Recommendations
- **Random Forest achieved the best balance between accuracy (0.75) and generalization (OSR² = 0.27)**, making it the most suitable model for financial institutions optimizing approvals.
- **CART had the highest accuracy (0.77)** but struggled with generalization (OSR² = 0.06), making it ideal for high interpretability but prone to overfitting.
- **Logistic Regression performed moderately (0.74 accuracy) and was best suited for fairness analysis**, but it struggled with recall, making it less effective for maximizing approvals.
- **Feature selection and bias analysis are crucial**, as some demographic groups showed lower approval rates, indicating systemic biases.
- **For financial institutions, Random Forest is recommended for predictive accuracy,** while **CART is useful for interpretable decision-making, and Logistic Regression helps analyze bias and fairness**.

