# Customer Churn Prediction

This project uses machine learning to predict whether telecom customers will cancel their service.

## Project Overview

Customer churn is a major challenge for telecom companies. In this project, I built a machine learning model using logistic regression to predict customer churn based on demographic and service usage features.

## Tools Used

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  

## Model Performance

The logistic regression model was trained on customer demographic and service data and evaluated using a test dataset.

Accuracy: 1.0

Evaluation metrics included:
- Confusion Matrix
- Precision
- Recall
- F1 Score

## Customer Churn Distribution

![Churn Distribution](churn_distribution.png)

## Top Features Influencing Churn

![Feature Importance](feature_importance.png)

## Dataset

The dataset contains telecom customer information including:
- tenure
- monthly charges
- contract type
- payment method
- internet service

These features were used to train the model.

## Future Improvements

- Test additional models such as Random Forest and XGBoost
- Perform cross-validation
- Address potential overfitting
