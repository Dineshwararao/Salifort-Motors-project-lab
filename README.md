###Predicting Employee Turnover
This project is part of the Google Advanced Data Analytics Professional Certificate and focuses on predicting employee turnover using machine learning techniques such as logistic regression, Decision Trees, Random Forest, and XGBoost.

#Capstone Project URL:
Google Advanced Data Analytics Capstone Project

##Business Problem
Salifort Motors is experiencing a high rate of employee turnover, leading to increased costs in recruitment, training, and upskilling. The goal is to predict which employees are likely to leave the company, allowing leadership to address the root causes and reduce turnover.

##Data Overview
The dataset used for this project, sourced from Kaggle, includes data on approximately 12,000 employees and 10 features per employee. The features cover key aspects such as:

#Satisfaction Level
#Last Evaluation Score
#Number of Projects
#Average Monthly Working Hours
#Tenure at the Company
#Work Accident Indicator
#Promotion in Last 5 Years
#Department
#Salary Level
#Turnover Status (whether the employee stayed or left)

##Feature Engineering
Feature engineering was applied to derive more predictive insights from the data. The most critical features identified for turnover prediction include:

#Number of projects an employee worked on.
#Tenure at the company.
#Last evaluation score.
#Whether the employee is overworked (working over 175 hours per month).
#Experience of a work accident.
#Salary level.

##Modeling Approach
Various machine learning models were tested to predict employee turnover:

#Logistic Regression
#Decision Tree
#Random Forest
#XGBoost

The XGBoost model with hyperparameter tuning and feature engineering provided the best results in terms of precision, recall, F1-score, and overall accuracy.

##Key Predictive Features
#Number of projects
#Tenure
#Last evaluation score
#Average working hours
#Work accident experience
#Salary level

##Model Evaluation
The performance of the XGBoost model was evaluated using the test set, and the following metrics were recorded:

#Precision: 90.1%
#Recall: 87.8%
#F1 Score: 89.0%
#Accuracy: 96.4%
#AUC: 97.0%

##Conclusion
The XGBoost model effectively predicts employee turnover, providing key insights into which employees are most likely to leave. By focusing on the top predictive features such as the number of projects, tenure, and last evaluation score, Salifort Motors can proactively address employee dissatisfaction and reduce turnover, leading to better retention and overall cost savings.
