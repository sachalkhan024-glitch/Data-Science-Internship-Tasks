# Data-Science-Internship-Tasks
My completed tasks for the Developers Hub Corporation Data Science & Analytics Internship

This repository contains my completed tasks for the Data Science & Analytics Internship at Developers Hub Corporation. 

> Task 1: Exploring and Visualizing a Simple Dataset (Iris)
* Objective: Understand how to read, summarize, and visualize a dataset.
* Approach: Loaded the Iris dataset using `pandas` and performed Exploratory Data Analysis (EDA) using `matplotlib` and `seaborn` to create scatter plots, histograms, and box plots.
* Results and Insights: Visualizations revealed clear clustering among different Iris species based on sepal and petal measurements. Box plots successfully highlighted outliers that would require handling in a predictive model.

> Task 2: Credit Risk Prediction
* Objective: Predict whether a loan applicant is likely to default on a loan.
* Approach: Handled missing data, performed EDA on applicant demographics, and trained a Logistic Regression classification model.
* Results and Insights: The model achieved an accuracy of 78.86%. Credit history was identified as the primary driver for loan approvals. The confusion matrix revealed the model has some risk tolerance, suggesting a need for stricter thresholds to minimize financial risk.

> Task 3: Customer Churn Prediction
* Objective: Identify customers who are likely to leave the bank.
* Approach: Cleaned the dataset, applied One-Hot Encoding for categorical features (Geography, Gender), and trained a Decision Tree classifier.
* Results and Insights: The model predicted churn with 78.05% accuracy. Feature importance analysis showed that a customer's Age is the primary factor influencing attrition, followed by their Estimated Salary and Account Balance. 

> Task 4: Predicting Insurance Claim Amounts
* Objective: Estimate the medical insurance claim amount based on personal data.
* Approach: Encoded categorical text data into numerical format and trained a Linear Regression model to predict continuous charges. 
* Results and Insights: The model achieved an R-squared score of 0.7836 with a Mean Absolute Error of $4,181.19. Correlation analysis proved that smoking status is the single most significant factor driving up insurance charges, followed by age and BMI.

> Task 5: Personal Loan Acceptance Prediction
* Objective: Predict which customers are likely to accept a personal loan offer.
* Approach: Processed the Bank Marketing Dataset, performed EDA on features like age and job, and trained a Decision Tree classifier to identify target customer groups.
* Results and Insights: The most important predictor for loan acceptance was the duration of the last contact, followed by previous campaign success. The bank should focus marketing efforts on individuals with a positive contact history and longer engagement times.
