# Credit-Card-Defaulter-Prediction
## Overview

This project aims to predict whether a customer will default on their credit card payment using machine learning techniques. It helps financial institutions identify high-risk customers and take preventive actions.

## Objectives
1. Predict credit card defaulters (0 = No, 1 = Yes)
2. Handle imbalanced dataset effectively
3. Compare multiple ML models
4. Improve prediction performance using tuning

## Dataset
Contains customer financial and demographic details
Features include:
1. Credit limit
2. Payment history (PAY_1 to PAY_6)
3. Bill amounts (BILL_AMT1–6)
4. Previous payments (PAY_AMT1–6)
5. Target variable: Default (0/1)


## Technologies Used
1. Python
2. Pandas, NumPy
3. Scikit-learn
4. Matplotlib
5. Flask (for deployment)


## Project Workflow
1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Handling Class Imbalance
6. Model Training
7. Model Evaluation
8. Deployment (Flask API)

## Machine Learning Models
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Naive Bayes
5. Support Vector Machine (SVM)

## Evaluation Metrics
1. Accuracy
2. Precision
3. Recall
4. F1-Score

## ⚠️ Special focus on Recall to correctly identify defaulters

## 📈 Results
1. Compared multiple models to select the best one
2. Achieved improved performance after handling imbalance
3. Final model provides reliable predictions for risk analysis

## UI
<img width="1366" height="768" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/745ff028-8f58-4deb-aa63-d14fde80ab88" />

## Code 
Best Model:
* Model            :   Accuracy
* Random Forest    --   0.708190
* LightGBM         --   0.708190
* SVM             --    0.703879
* Naive Bayes    --     0.681466
* XGBoost        --     0.681466
* KNN            --     0.668966
* Logistic Reg    --    0.667241
* Decision Tree   --    0.635345
