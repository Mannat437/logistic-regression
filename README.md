# Logistic Regression – Customer Churn Prediction

This repository contains a complete, end-to-end implementation of a
**Logistic Regression model for Customer Churn Prediction**.

The focus of this project is not only on building a classifier, but on
understanding **classification thinking**, **probability-based predictions**,
and **proper evaluation metrics** used in real-world machine learning problems.

This project is part of my **Classical Machine Learning Foundations** roadmap.

---

## Problem Statement

Customer churn prediction aims to identify whether a customer is likely to
leave a service.

This is a **binary classification problem**:
- 0 → Customer does not churn
- 1 → Customer churns

Churn prediction is widely used in telecom, banking, SaaS, and subscription-based
businesses, where retaining customers is critical.

---

## Dataset

- **Dataset:** Telco Customer Churn
- Each row represents a single customer
- Target variable: `Churn`

### Feature Types
- Numerical: `tenure`, `MonthlyCharges`, `TotalCharges`
- Binary categorical: `Partner`, `Dependents`, `PhoneService`, etc.
- Multi-class categorical: `Contract`, `InternetService`, `PaymentMethod`, etc.

The dataset contains a large number of categorical features, making preprocessing
a key part of this project.


---

## Workflow Overview

The project follows a clear and structured machine learning workflow:

1. Data loading and understanding
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Encoding categorical variables
5. Train–test split with stratification
6. Feature scaling
7. Logistic Regression model training
8. Model evaluation using appropriate metrics
9. Threshold tuning and interpretation

All steps are implemented in a **single, well-documented notebook** for clarity.

---

## Model Evaluation

The model is evaluated using:
- Confusion Matrix
- Precision
- Recall
- F1-score
- ROC–AUC

Accuracy is not used as the sole metric due to class imbalance.
Greater emphasis is placed on **recall**, as missing churned customers
can be costly in real-world applications.

---

## Key Learnings

- Logistic Regression outputs probabilities, not just class labels
- Preprocessing is often more important than model choice
- Class imbalance requires careful metric selection
- Threshold tuning allows business-driven decision making
- Logistic Regression provides strong interpretability but is limited
  by linear decision boundaries

---

## Limitations

- The model cannot capture complex non-linear relationships
- Performance may be improved using tree-based or ensemble models
- Feature interactions are not modeled explicitly

---

## Conclusion

Logistic Regression serves as a strong and interpretable baseline for
customer churn prediction.

This project demonstrates the importance of:
- Thoughtful EDA
- Correct preprocessing
- Proper evaluation metrics
- Clear separation between probabilities and decisions

---

## Author

Mannat  
B.Tech – Artificial Intelligence and Machine Learning  

This repository is part of a structured learning journey focused on building
strong theoretical foundations along with practical machine learning skills.
