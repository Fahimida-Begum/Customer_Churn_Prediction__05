👉Project Overview
Customer churn is one of the biggest challenges in telecom and subscription-based businesses. This project aims to predict whether a customer will churn (leave the service) using Machine Learning models.

✍️Problem Statement
Build a Model to predict which customers are likely to churn using Machine Learning

Task : 
Perform exploratory Data analysis and predictive modelling and make sure below steps are addressed 

-Churn Prediction Model
1. Build a classification model to predict which customers are likely to churn.
   
2. Must compare at least 3 different algorithms (e.g., Logistic Regression, Random Forest, XGBoost)
  
3. What are the top 5 most important features driving churn predictions?

📁 Project Structure
Customer-Churn-Prediction/
│

├── datasets/

     └──DataDescription.txt
|

     └──Telco_Customer_Churn.xlsx

├──Churn_Prediction.ipynb

└── README.md

✍️📃Step-by-Step Workflow

1.Importing the libraries

2.Load the DataSet

3.Data Cleaning

4.Exploratary Data Analysis

5.Splitting Data into Training and Testing Data

6.Model Building

7.Comparing the Models

8.Finding the top 5 most important features  churn predictions

📂 Dataset Information

7043 observations with 33 variables
-Churn Value (Target Variable)

Target Variable:
0 → No Churn
1 → Churn

🤖 Models Used

-Logistic Regression

-Random Forest

-XGBoost

👉Better Performance: XGBoost

Accuracy: 79.9%

ROC-AUC Score: 0.85

Better performance in identifying non-churn customers

