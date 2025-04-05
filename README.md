# telco-customer-churn
A classification project predicting customer churn using ML models.
Telco Customer Churn Prediction
This project focuses on predicting customer churn for a telecom company using machine learning models. The goal is to identify customers who are likely to stop using the service and understand the factors influencing their decision.

Problem Statement
Telecom companies face significant losses due to customer churn. By identifying customers at risk, companies can proactively take measures to retain them. This project aims to build a classification model that predicts churn based on customer demographics, services used, account information, and other behavioral factors.

Dataset
The dataset contains information about telecom customers, such as:

Demographic data (gender, senior citizen, partner, dependents)

Services availed (internet service, online security, tech support, etc.)

Payment and contract details

Tenure and total charges

Churn status (target variable)

Exploratory Data Analysis (EDA)
Key insights:

Customers with month-to-month contracts are more likely to churn.

Higher churn is observed among customers without tech support or online security.

Tenure and contract type have strong influence on churn.

Fiber optic internet users showed higher churn probability than DSL users.

Models Used
Several models were tested to evaluate performance:

Model	Accuracy	ROC-AUC
Logistic Regression	✅ High	✅ Good
Random Forest	✅ High	✅ Great
XGBoost	✅ High	✅ Excellent
All models were evaluated based on accuracy, confusion matrix, classification report, and ROC-AUC curves.

XGBoost performed the best in terms of generalization and interpretability.

Key Findings
Contract type and tenure are critical churn indicators

Customers with automatic payments tend to stay longer

Providing tech support & online security may reduce churn

What I Learned
Uhmm, this was one of my favorite projects where I finally felt confident combining EDA, feature engineering, feature selection and model comparison into one clear storyline. I realized how important data preprocessing and interpretability are in real-life classification problems.
