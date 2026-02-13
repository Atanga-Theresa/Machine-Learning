Employee Retention Analysis

Project Overview

This project focuses on analyzing employee data to understand and predict employee retention. It involves conducting exploratory data analysis (EDA) to identify key variables that influence whether employees leave or stay with the company. Visual insights are generated to illustrate the impact of factors such as employee salaries and department affiliations on retention rates. Finally, a logistic regression model is constructed using the identified impactful variables, and its predictive capability regarding employee turnover is assessed.

Project Objectives
The primary objectives of this project are:

Data Exploration: Conduct exploratory data analysis to identify key variables impacting employee retention.

Visual Insights: Generate visual insights through bar charts illustrating the influence of employee salaries and department affiliations on retention rates.

Predictive Modeling: Construct a logistic regression model using impactful variables to predict employee turnover.

Model Evaluation: Measure the accuracy and predictive capability of the logistic regression model.

Methodology
Data Loading and Initial Inspection: Loaded employee HR data from a CSV file into a pandas DataFrame.

Data Cleaning: Checked for and handled null values and duplicate rows to ensure data integrity. Duplicate rows were identified and removed.

Exploratory Data Analysis (EDA)

Compared average satisfaction levels between employees who stayed and those who left.

Analyzed average monthly hours and time spent in the company for employees who stayed versus left.

Examined the relationship between salary levels and employee retention.

Investigated the impact of promotion in the last 5 years on retention.

Explored retention rates across different departments.

Feature Engineering: Categorical variables ('salary' and 'Department') were one-hot encoded to prepare the data for modeling.

Model Building (Logistic Regression)

The dataset was split into training and testing sets.

A Logistic Regression model was initialized and trained on the preprocessed data.

Model Evaluation: The model's performance was assessed using accuracy score, confusion matrix, classification report, and ROC-AUC score.

Key Findings and Insights

Satisfaction Level: Employees who left had significantly lower average satisfaction levels compared to those who stayed, highlighting satisfaction as a critical retention factor.

Average Monthly Hours: Employees who left tended to work slightly more hours on average, suggesting potential burnout or workload issues.

Time Spent in Company: Employees who left had spent a slightly longer average time in the company, possibly indicating a tenure-based departure pattern.

Salary Level: A strong inverse correlation was observed, where employees with lower salaries were significantly more likely to leave, while those with high salaries showed strong retention.

Promotion: Employees who received promotions in the last five years had a much higher retention rate.

Department: Retention rates varied significantly across departments, with Sales, Technical, and Support departments showing higher turnover compared to Management and RandD.

Model Performance
The Logistic Regression model achieved an accuracy of approximately 79.21%.

Classification Report:

              precision    recall  f1-score   support

           0       0.82      0.94      0.88      3007
           1       0.50      0.23      0.32       789

    accuracy                           0.79      3796
   macro avg       0.66      0.59      0.60      3796
weighted avg       0.76      0.79      0.76      3796
The ROC-AUC score of 0.8285 indicates that the model effectively distinguishes between employees likely to leave and those likely to stay.

Contact
Atangatheresa@outlook.com
