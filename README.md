# 📊 Customer Churn Prediction & Analysis

## 🚀 Project Overview
This project focuses on predicting customer churn using machine learning models and extracting actionable business insights from the Telco Customer Churn dataset.

The goal is to help businesses identify customers at risk of leaving and understand the key factors driving churn.

---

## 🧠 Models Used
Three different models were implemented and compared:

- Linear Regression (Baseline)
- Random Forest (Improved)
- XGBoost (Final Model)

Hyperparameter tuning was performed to optimize performance, and the best model was selected based on evaluation metrics.

---

## 🏆 Final Model: XGBoost
XGBoost delivered the most balanced and reliable performance, especially in identifying churned customers (high recall).

### 📈 Performance Summary

Class 0 (Non-Churn):  
Precision: 0.92 | Recall: 0.66 | F1-score: 0.77  

Class 1 (Churn):  
Precision: 0.47 | Recall: 0.84 | F1-score: 0.61  

Recall Accuracy for Churning Customers -> 84%

👉 The model is optimized for high recall on churn customers, ensuring fewer missed churn cases — which is critical for business retention strategies.

---

## 📊 Key Business Insights
- Month-to-month customers show significantly higher churn compared to long-term contracts  
- Customers with low tenure (≤ 1 year) are more likely to churn  
- Churn varies across internet services and online feature usage  
- Certain service combinations increase churn probability  

---

## 🛠️ Tech Stack
- Python  
- Scikit-learn  
- XGBoost  
- Pandas, NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## ⚙️ Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training & Comparison  
5. Hyperparameter Tuning  
6. Model Evaluation  
7. Business Insight Extraction  

---

## 📂 Dataset
- Telco Customer Churn Dataset (~7,000+ records)

---

## 📌 Key Highlights
- Compared multiple ML models to ensure robust selection  
- Focused on business-oriented evaluation (recall for churn)  
- Extracted actionable insights beyond prediction  
- Built an end-to-end ML pipeline  

---

## 🔮 Future Improvements
- Deploy using Flask / FastAPI  
- Real-time churn prediction system  
- Advanced feature engineering  

---

## 🤝 Contribution
Feel free to fork, contribute, or suggest improvements!
