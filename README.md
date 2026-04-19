# Credit-Card-Defaulter-Prediction
📌 Overview

This project aims to predict whether a customer will default on their credit card payment using machine learning techniques. It helps financial institutions identify high-risk customers and take preventive actions.

🎯 Objectives
Predict credit card defaulters (0 = No, 1 = Yes)
Handle imbalanced dataset effectively
Compare multiple ML models
Improve prediction performance using tuning
📁 Dataset
Contains customer financial and demographic details
Features include:
Credit limit
Payment history (PAY_1 to PAY_6)
Bill amounts (BILL_AMT1–6)
Previous payments (PAY_AMT1–6)
Target variable: Default (0/1)
⚙️ Technologies Used
Python 🐍
Pandas, NumPy
Scikit-learn
Matplotlib
Flask (for deployment)
🔄 Project Workflow
Data Collection
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Handling Class Imbalance
Model Training
Model Evaluation
Deployment (Flask API)
🤖 Machine Learning Models
Logistic Regression
Decision Tree
Random Forest
Naive Bayes
Support Vector Machine (SVM)
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1-Score

⚠️ Special focus on Recall to correctly identify defaulters

📈 Results
Compared multiple models to select the best one
Achieved improved performance after handling imbalance
Final model provides reliable predictions for risk analysis
