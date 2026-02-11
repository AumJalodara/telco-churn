Telco Customer Churn Prediction
-Overview

This project focuses on predicting whether a customer will churn (leave the service) using the Telco Customer Churn dataset. The aim was to build a simple and clear machine learning pipeline starting from data cleaning to model evaluation and comparison.

The task was completed as part of a machine learning internship assignment.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
-Dataset

The dataset contains customer information such as services used, billing details, and demographics.
The target variable is Churn, which indicates whether a customer left the service.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
-Data Preparation

Before training the models, the dataset was cleaned and prepared:

Removed unnecessary columns like customerID

Converted categorical values (Yes/No) into numeric form
--------------------------------------------------------------------------------------------------------------------------------------------------------------
-Handled missing values

Applied encoding to categorical features

These steps ensured the data was suitable for machine learning models.
----------------------------------------------------------------------------------------------------------------------------------------------------------
-Train/Test Split Method

To evaluate the model properly, the dataset was divided into:

80% training data

20% testing data

The models were trained on the training data and evaluated on the test data to check how well they perform on unseen customers.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
-Models Trained

The following models were trained and compared:

Logistic Regression (baseline model)

Random Forest

XGBoost

Logistic Regression was used as a simple baseline, while Random Forest and XGBoost were tested as more advanced models.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
-Evaluation Metrics

Model performance was measured using:

Accuracy

Precision

Recall

F1-score
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
-Confusion Matrix

These metrics help understand not just overall correctness but also how well the model identifies customers who are likely to churn.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Results

Logistic Regression Accuracy: 82%

Random Forest Accuracy: 79%

XGBoost Accuracy: 81%
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Best Result

The best performing model was Logistic Regression, achieving an accuracy of 82% on the test dataset.
It provided the most balanced and reliable performance for this churn prediction task.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Conclusion

This project demonstrates the full workflow of a tabular machine learning problem — from data preprocessing and exploratory analysis to model training and evaluation.

Although more complex models were tested, Logistic Regression performed best on this dataset, showing that simpler models can sometimes capture patterns effectively.
