# telco-customer-churn
A classification project predicting customer churn using ML models.

# Telco Customer Churn Prediction

This project focuses on predicting **customer churn** for a telecom company using machine learning models. The goal is to identify customers who are likely to stop using the service and understand the factors influencing their decision.

---

## Problem Statement

Customer churn is a major challenge in the telecom industry. Losing customers affects both revenue and brand trust. By predicting churn early, companies can take preventive steps to retain valuable customers.

---

## Dataset Overview

The dataset includes information such as:
- **Customer demographics** (gender, senior citizen, partner, dependents)
- **Service subscriptions** (phone, internet, online security, streaming)
- **Account info** (tenure, contract, payment method, charges)
- **Target variable**: `Churn`

---

## Exploratory Data Analysis (EDA)

Key observations:
- **Contract type** and **tenure** have a strong influence on churn.
- Customers with **month-to-month** contracts are more likely to leave.
- **Tech support** and **online security** services seem to reduce churn.
- **Senior citizens** have a slightly higher churn rate.

---

---

## Models Tried

I tested several classification models and compared them using accuracy, precision, recall, F1-score, and ROC-AUC.

| Model                | Accuracy | ROC-AUC |
|---------------------|----------|---------|
| Logistic Regression | ✅ Good  | ✅ Good |
| Random Forest       | ✅ Better | ✅ Better |
| XGBoost             | ✅ Best | ✅ Excellent |

**XGBoost** gave the best balance of accuracy and generalization.

---

## Key Takeaways

- Customers with **long-term contracts** are less likely to churn.
- **Automatic payments** and **paperless billing** also correlate with lower churn.
- Features like **tenure**, **contract**, **tech support**, and **internet service** were most influential.

---

## What I Learned

This project really helped me understand how feature relationships and good preprocessing can improve model performance. It also made me more confident in evaluating classification models and presenting business-relevant insights.

---

