# Customer-Churn-Analysis-

# 📊 Customer Churn Prediction – Telecom Dataset

This project presents an end-to-end pipeline for predicting customer churn using telecom data. The process includes detailed exploratory data analysis (EDA), feature engineering, model building, and deployment using Flask.

## 🔍 Project Overview

- Performed comprehensive Exploratory Data Analysis (EDA) to identify trends, patterns, and characteristics associated with customer churn.
- Analyzed customer behavior to detect key factors contributing to churn, such as contract type, tenure, payment method, etc.
- Addressed class imbalance using **SMOTE** oversampling to ensure model fairness and accuracy.

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Random Forest Classifier** for churn prediction
- **SMOTE** for handling imbalanced data
- **Flask** for model deployment
- **Jupyter Notebook** for analysis and development

## 🚀 Model Performance

- Achieved **94% accuracy** on the test set
- Attained **97% recall** for the churn class
- Reduced false negatives to only 22 out of 1,160 test samples

## 🌐 Deployment

The final model was deployed using Flask, allowing for real-time predictions based on user inputs. This simulates how businesses can integrate churn prediction models into their customer service platforms to flag at-risk customers.



