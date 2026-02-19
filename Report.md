# Titanic Survival Prediction – Project Report

## 1. Objective
The goal of this project is to build a predictive machine learning model
to determine whether a passenger survived the Titanic disaster.

## 2. Dataset
The Titanic dataset contains passenger demographic and travel-related
information such as age, gender, ticket class, fare, and embarkation port.

The target variable is `survived`.

## 3. Data Preprocessing
- Missing numerical values (age) handled using median
- Missing categorical values handled using most frequent value
- Categorical variables encoded using One-Hot Encoding
- Pipelines used to prevent data leakage

## 4. Model Selection
Logistic Regression was selected due to:
- Binary target variable
- Interpretability
- Strong baseline performance

## 5. Model Performance
- Accuracy achieved: approximately 78–80%
- Balanced precision and recall for both classes

## 6. Conclusion
The Logistic Regression model successfully learned survival patterns.
Proper preprocessing significantly improved performance.
This approach provides a strong baseline for future improvements.
