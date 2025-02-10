# Heart Attact Prediction 
Overview

This project aims to predict the risk of a heart attack based on various health-related parameters using different machine learning models. The dataset contains multiple features such as age, cholesterol levels, blood pressure, and other lifestyle factors. By training different models, we assess which algorithm performs best in predicting heart attack risk.

Dataset

Source: Kaggle

Number of Records: 50,000

Number of Features: 19

Key Features:

Age

Gender

Smoking

Cholesterol Level

Hypertension

Heart Rate

Exercise-Induced Angina

Blood Pressure

Family History

Project Workflow

Data Preprocessing:

Handle missing values.

Encode categorical variables.

Scale numerical values.

Remove outliers.

Feature selection.

Model Training:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

XGBoost

Hyperparameter Tuning:

Used GridSearchCV to optimize parameters.

Decision Tree showed significant improvement after tuning.

Model Evaluation:

Accuracy

Mean Squared Error (MSE)

Confusion Matrix

Classification Report

Results Summary

Model

Accuracy

Logistic Regression

50.00%

Decision Tree

49.89%

Random Forest

48.93%

SVM

50.04%

XGBoost

48.98%

The Decision Tree model improved significantly with hyperparameter tuning.

The overall accuracy remained low, suggesting more complex models like Neural Networks may be needed.

Installation & Setup

Future Improvements

Implementing Neural Networks to better handle non-linearity.

Collecting more diverse health-related data to improve predictions.

Using ensemble methods like stacking different models.

Experimenting with deep learning architectures.
