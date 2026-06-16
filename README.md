Customer Churn Prediction System
Machine Learning Approach for Predicting Customer Retention

Customer Churn Prediction System is a machine learning project designed to analyze customer behavior and predict whether a telecom customer is likely to leave the service.

The system is built using classical machine learning models and follows a complete data science pipeline including preprocessing, encoding, model training, evaluation, and prediction.

Project Objective

The main objective of this project is to identify customers who are at risk of churning by analyzing their demographic and service-related attributes such as:

Contract type
Monthly charges
Total charges
Tenure
Payment method

The model helps understand customer behavior patterns and supports business retention strategies.

Methodology

The project follows a structured machine learning workflow:

Data preprocessing and cleaning
Handling missing values in TotalCharges
Feature encoding (categorical → numerical transformation)
Train-test split
Feature scaling (StandardScaler)
Model training and evaluation
Customer-level prediction testing
Models Used

The following machine learning models were implemented:

Logistic Regression (baseline model)
Random Forest Classifier
Random Forest (class-balanced version)
XGBoost Classifier

Each model was evaluated and compared based on classification performance metrics.

Evaluation Metrics

Model performance was measured using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix
Classification Report
Feature Importance Analysis

Random Forest model was used to extract feature importance values in order to understand the most influential factors affecting churn behavior.

The most important features include:

Customer tenure
Monthly charges
Contract type
Payment method
Prediction System

The trained XGBoost model was tested with manually created customer profiles to simulate real-world prediction scenarios.

The system outputs:

Churn prediction (Yes / No)
Probability of churn
Risk level interpretation
Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Key Insights
Short tenure customers are more likely to churn
Higher monthly charges increase churn probability
Long-term contracts significantly reduce churn risk
Payment method is a strong behavioral indicator
Future Improvements
Hyperparameter tuning for XGBoost and Random Forest
Cross-validation for better generalization
Deployment using FastAPI
Web interface for real-time prediction
ML pipeline structuring (production-ready version)
Author

Eren Oğan
Computer Engineering Student
Focus: Machine Learning & AI Systems

Project Summary

This project demonstrates a complete machine learning workflow for a real-world classification problem. It includes data preprocessing, multiple model training, evaluation, and practical prediction use cases for customer churn analysis.
