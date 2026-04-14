# 💳 Credit Card Fraud Detection

## 📌 Problem
Credit card fraud detection is a highly imbalanced classification problem where fraudulent transactions are extremely rare compared to normal transactions.

---

## What i did in this Project 🚀: 
- handled imbalanced data  
- compared models  
- made decisions  

## 📊 Dataset:
- PCA-transformed features: V1–V28  
- Additional features: Time, Amount  
- Target:  
  - 0 → Normal  
  - 1 → Fraud  

---

## ⚙️ Approach
- Performed Exploratory Data Analysis (EDA)
- Visualized class imbalance and feature distributions
- Tested multiple models:
  - Logistic Regression
  - Random Forest ✅ (Final Model)
  - XGBoost
- All were tested with SMOTE and Without SMOTE

- Evaluated using:
  - Precision
  - Recall
  - F1-score
  - ROC-AUC Curve

---

## 🏆 Final Model: Random Forest
- Random Forest resulted in balanced Precision and Recall compared to other models without SMOTE!

### 📈 Performance
- Precision (Fraud): **94.12**
- Recall (Fraud): **81.63**
- F1-score: **99.95**
- ROC-AUC: **96.30**

---

## 📊 Visualizations
- ROC-AUC Curve  
- Confusion Matrix  
- Feature Importance  
- Classification Report  

---

## 📁 Project Structure :
fraud-detection/
│
├── models/
├── notebooks/
├── reports/
├── README.md

---

 
---

## 🚀 Conclusion
Random Forest provided the best balance between precision and recall without requiring additional techniques like SMOTE. The model effectively detects fraudulent transactions while minimizing false positives.

---

## Tools Used 🔎:

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Joblib
- XGBOOST
