![alexander-mils-lCPhGxs7pww-unsplash](https://user-images.githubusercontent.com/102637138/220388499-8c9b370b-60e3-424d-a914-280f53b76b77.jpg)

# Project Problem
The company experienced problems in loan members to customers. Customers who return to return or pay off loans according to the promised time and nominal period, will certainly harm the company. At present, company managers want to judge which customers are appropriate to be given credit and which are not feasible. They have data about customers obtained when customers fill out online forms. Managers want to create a data analysis to identify customer segments so that they can target who will be given a loan. In other words, the prediction model will greatly help them in making business decisions.

# The purpose of this project is to predict the person who will make a loan, whether it is worth approved or not. In addition to predicting, this project will also conduct related data analysis to find information and knowledge as a basis for making business decisions. What will be done in this project are:
1. Exploratory Data Analysis (EDA) to view and find out the characteristics of data.
2. Missing Value, Outliers, and Manipulating Data.
3. Analyze data to find out information about the variables to be used in the prediction model
4. Conduct label encoding and standardization by making pipelines
5. Create a model using regression logistics and decision tree

This project consists of two parts:
1. Prepare Data
    - Import
    - Exploratory Data Analysis (EDA)
    - Analyze
    - Feature Engineering
2. Build Model
    - Logistic Regression 
        - Basline
        - Iterate
        - Evaluate
    - Decision Tree Classifier
        - Baseline
        - Hyperparameter tunning and Iterate
        - Evaluate
        
# Data Description
1. Loan_ID: Unique Loan Number
2. Gender: The gender of the loan applicant
3. Married: The marital status of the loan applicant
4. Dependents: Number of dependents of children or family
5. Education: The education status of the loan applicant
6. Self_Employed: Loan applicant job status
7. ApplicantIncome: Applicant's monthly income
8. Coapplicantincome: Applicant's side income
9. Loan Amount: Total loan
10. Loan_Amount_Term: loan period
11. Credit History: Quality of Credit History. 1: Good, 0: Bad
12. Property Area: Loan applicant property location
13. Loan_Status: Loan Status (Y: Accepted, N: Non Accepted)

# References

https://www.kaggle.com/code/simtoor/loan-prediction-svm/notebook

https://www.kaggle.com/code/caesarmario/loan-prediction-w-various-ml-models#6.-Models-%F0%9F%9B%A0
