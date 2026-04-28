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
<img width="1366" height="768" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/2ea4412f-ddbd-4f5b-8e45-ca64badc868f" />
<img width="1366" height="768" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/d7a0a661-9ebb-4848-8491-9f1b7d6df4e8" />
<img width="1366" height="768" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/8f1b30d1-bcba-4ccb-bf8a-086edd3e3534" />



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


## 📌 Project Summary: Credit Card Default Prediction

This project focuses on predicting whether a credit card customer is likely to default on their payment in the next billing cycle. Credit card default is a major issue for financial institutions, as it directly impacts revenue, risk management, and customer trust.

The objective of this project is to build a machine learning model that can accurately classify customers into two categories: defaulters (1) and non-defaulters (0) based on their historical financial and behavioral data. The dataset includes features such as credit limit, payment history, bill statements, previous payments, and demographic details.

Several machine learning algorithms such as Logistic Regression, Decision Tree, Random Forest, Naive Bayes, and Support Vector Machine are implemented and compared to identify the best-performing model. Data preprocessing techniques like handling missing values, feature scaling, and outlier removal are applied to improve model performance. Additionally, techniques for handling class imbalance (such as resampling and class weighting) are used to ensure fair and reliable predictions.

The performance of the models is evaluated using metrics like accuracy, precision, recall, and F1-score, with special emphasis on recall to correctly identify defaulters. The final model helps financial institutions in early detection of risky customers, enabling them to take preventive actions such as adjusting credit limits or issuing warnings.

Overall, this project demonstrates how machine learning can be effectively used in the financial sector to reduce risk, improve decision-making, and enhance customer management.
