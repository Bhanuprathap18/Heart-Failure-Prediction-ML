# Heart Failure Prediction Using Machine Learning

## Overview

This project focuses on predicting mortality risk among heart failure patients using machine learning techniques.

The target variable is `DEATH_EVENT`, where:
- `0` = Patient survived
- `1` = Patient did not survive

## Objectives

- Analyze clinical and demographic factors associated with heart failure outcomes.
- Preprocess and prepare patient data for machine learning.
- Train and compare multiple machine learning models.
- Evaluate model performance using standard classification metrics.
- Identify high-risk patients through predictive modeling.

## Machine Learning Models

The project evaluates:

- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Neural Network (MLP)

Hyperparameter tuning and cross-validation are used to improve model reliability.

## Features

The dataset contains clinical and demographic variables such as:

- Age
- Anaemia
- Creatinine Phosphokinase (CPK)
- Diabetes
- Ejection Fraction
- High Blood Pressure
- Platelets
- Serum Creatinine
- Serum Sodium
- Sex
- Smoking
- Time

## Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Project Structure

```text
Heart-Failure-Prediction-ML/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── Heart_Failure_Prediction.ipynb
└── Presentation/
    └── ML Presentation.pptx
