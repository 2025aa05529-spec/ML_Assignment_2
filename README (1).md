
# ML Assignment 2 - Classification Models Deployment

## Problem Statement
The objective of this assignment is to build, evaluate, and deploy multiple machine learning classification models to predict the presence of heart disease. The project demonstrates an end-to-end workflow including model training, evaluation, comparison, and deployment using Streamlit Community Cloud.

## Dataset Description
The dataset used is the Heart Disease Dataset from the UCI Machine Learning Repository.

Number of Instances: 1025

Number of Features: 13

Target Variable: Binary (0 = No Disease, 1 = Disease)

Type: Binary Classification

Features include:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

Resting ECG

Maximum Heart Rate

Exercise Induced Angina

ST Depression

Slope

Number of Major Vessels

Thalassemia

## Models Used
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Naive Bayes
- Random Forest (Ensemble)
- XGBoost (Ensemble)

## Evaluation Metrics
Accuracy, AUC, Precision, Recall, F1 Score, MCC

## Observations
- Logistic Regression: Performs well on linearly separable patterns and provides stable baseline accuracy.
- Decision Tree: Captures non-linear relationships but may overfit without pruning.
- KNN: Sensitive to feature scaling and value of k; performs moderately well
- Naive Bayes: Fast and efficient but assumes feature independence, which may reduce performance.
- Random Forest: Provides strong performance due to ensemble averaging and reduces overfitting.
- XGBoost: Achieved the best performance with highest accuracy and AUC due to boosting and regularization mechanisms

## Deployment
The application is deployed on Streamlit Community Cloud.
