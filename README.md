# ecommerce-churn-mlflow-project
# 🛒 Ecommerce Customer Churn Prediction with MLflow  

## 📌 Project Overview  
Customer churn is one of the biggest challenges for ecommerce platforms. Retaining an existing customer is **5x cheaper** than acquiring a new one. This project aims to predict the likelihood of customer churn using historical purchase and engagement data.  

We will track experiments and model performance using **MLflow**, enabling reproducibility, model comparison, and scalable deployment.  

---

## 🎯 Business Importance  
- **Revenue Impact**: Reducing churn by just 5% can boost profits by **25-95%**.  
- **Customer Retention**: Helps marketing teams design personalized campaigns.  
- **Resource Allocation**: Identifies at-risk customers → allocate retention budget wisely.  
- **Scalable ML Pipeline**: MLflow provides experiment tracking, reproducibility, and deployment readiness.  

---

## 🧠 Problem Statement  
**Objective**: Predict whether a customer will churn in the next period based on their behavioral and transactional history.  

**Hypothesis**:  
- Customers with **low purchase frequency**, **reduced site activity**, and **delayed repeat purchases** are more likely to churn.  
- Strong engagement (loyalty programs, frequent logins, positive reviews) reduces churn risk.  

---

## 📊 Dataset (Real-world inspired)  
Features may include:  
- `customer_id`  
- `total_orders`  
- `average_order_value`  
- `days_since_last_purchase`  
- `customer_segment`  
- `loyalty_points`  
- `site_visits_last_30_days`  
- `churn` (target: 1 = churned, 0 = retained)  

*(We’ll either use a synthetic ecommerce dataset or adapt a real-world open dataset to mimic ecommerce churn scenarios.)*  

---

## ⚙️ Tech Stack  
- **Python 3.10**  
- **Pandas / NumPy** → Data processing  
- **Scikit-learn** → Modeling (Logistic Regression, Random Forest, XGBoost, etc.)  
- **MLflow** → Experiment tracking, metrics logging, artifact storage  
- **Matplotlib / Seaborn** → Visualization  
- **GitHub** → Version control and collaboration  

---

## 🚀 Workflow  
1. Data exploration and feature engineering  
2. Baseline model (Logistic Regression)  
3. Advanced models (Tree-based, Ensemble, etc.)  
4. Track experiments using **MLflow**  
5. Log metrics (Accuracy, Precision, Recall, ROC-AUC, Custom Retention Metrics)  
6. Save models & artifacts for reproducibility  
7. Evaluate business implications of results  

---

## 📈 Expected Outcome  
- Identify top predictors of churn  
- Build a reproducible pipeline for churn prediction  
- Provide actionable insights for marketing & retention teams  
- Demonstrate **MLflow capabilities** in real-world ML project lifecycle  

--- 
