# Loan-Approval-Prediction-Problem
Loans are the core business of banks. The main profit comes directly from the loan’s interest. The loan companies grant a loan after an intensive process of verification and validation. However, they still don’t have assurance if the applicant is able to repay the loan with no difficulties. In this project, we’ll build a predictive model to predict if an applicant is able to repay the lending company or not. We work on the dataset that has been provided by Kaggle and we are going to use various models to predict the target variable.

# Data Information
We have downloaded the dataset from https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset/notebooks?sortBy=hotness&group=everyone&pageSize=20&datasetId=137197&outputType=all
For this problem, we have CSV files: train, test. 
Train file will be used for training the model, i.e. our model will learn from this file. It contains all the independent variables and the target variable.
Test file contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data.

# Approach for Problem Solving
1. Understanding the Problem  
2. Downloading the Dataset
3. Importing necessary Dependencies
4. Univariate and Bivariate Analysis
5. Feature Engineering
6. Data Pre-processing
7. Building the Model
9. Evaluation of the Model
10. End Results

# End Results
- After all the possible experiments Maximum accuracy of **89.34%** is achieved by using **SVM** and by making data balanced as **Up Sampling.**
- Surprisingly XGB Classifier does not give the accuracy better than SVM.
