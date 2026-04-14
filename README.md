# Credit Card Fraud Detection

## Problem
Detecting the fraudulent transactions using machine learning (ML) on highly imbalanced data.

## Dataset
- PCA-transformed features (V1–V28)
- Time and Amount
- Target: Class (0 = normal, 1 = fraud)

## Approach
- Performed EDA (Exploratory data analysis)
- Tested Logistic Regression, Random Forest, XGBoost
- Along with SMOTE and without SMOTE
- Selected Random Forest as final model

## Results
- Precision: 94.12
- Recall:  81.63
- ROC: 96.30
- Accuracy : 99.96

## Conclusion
Random Forest provided the best balanced between precision and recall without requiring SMOTE then other models  XGboost , Logistic Regression.



## How to Run
- Install requirements ( checkout Requirement.txt)
- Run notebooks 

## Tools :
- Python
- Pandas
- Scikit-Learn
- Joblib (for Saving the model)
- Matplotlib
- Seaborn
