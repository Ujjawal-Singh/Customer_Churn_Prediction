# 📉 Telecom Customer Churn Prediction

Welcome to the **Telecom Customer Churn Prediction** project! This repository contains a machine learning solution designed to predict customer churn and provide insights to help telecom companies retain customers effectively.

---

## 📜 Table of Contents
### Importing Libraries
# Loading Dataset
# Exploratory Data Analysis
# Outliers using IQR method
# Cleaning and Transforming Data
# One-hot Encoding
# Rearranging Columns
# Feature Scaling
# Feature Selection
# Prediction using Logistic Regression
# Prediction using Support Vector Classifier
# Prediction using Decision Tree Classifier
# Prediction using KNN Classifier

---

## 🧐 Overview
Customer churn refers to customers ending their association with a business. For telecom companies, churn has significant financial implications. This project focuses on:  
- Analyzing customer data to uncover churn patterns.  
- Building machine learning models to predict churn risk.  
- Providing actionable insights for retention strategies.  

---

## ✨ Features
- **Data Analysis**:  
  Understand customer behavior with visualizations and trend analysis.  

- **Data Preprocessing**:  
  - Handle missing values and outliers.  
  - Encode categorical features and scale numerical data.  

- **Machine Learning Models**:  
  - Logistic Regression  
  - Decision Trees  
  - Random Forest  
  - Support Vector Machines (SVM)  
  - Gradient Boosting (XGBoost, LightGBM)  

- **Model Evaluation**:  
  - Key metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
  - Confusion matrix and feature importance visualization.  

- **Actionable Insights**:  
  Identify high-risk customers and provide recommendations for retention.  

---

## 🛠 Technologies Used
- **Python Libraries**:  
  - Data Analysis: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`, `xgboost`  
  - Hyperparameter Tuning: `GridSearchCV`  

---

## 📂 Dataset
The dataset includes:  
- **Customer Demographics**: Gender, Seniority, etc.  
- **Service Details**: Contract type, Internet service, etc.  
- **Account Information**: Tenure, Monthly charges, etc.  
- **Churn Label**: Indicates if a customer left the service.  

**Source**: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  

---

## ⚙ Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/telecom-churn-prediction.git
   cd telecom-churn-prediction

