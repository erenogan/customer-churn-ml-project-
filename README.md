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

TR
Customer Churn Prediction System
Machine Learning Approach for Predicting Customer Retention

Customer Churn Prediction System, bir telekom şirketindeki müşterilerin hizmeti bırakıp bırakmayacağını tahmin etmek için geliştirilmiş bir makine öğrenmesi projesidir.

Bu sistem, klasik makine öğrenmesi algoritmaları kullanılarak oluşturulmuş ve uçtan uca veri işleme, modelleme ve tahmin pipeline’ı içermektedir.

Project Objective / Proje Amacı

The main objective of this project is to identify customers who are likely to churn using behavioral and service-related data.

Bu projenin amacı, müşteri davranışlarını analiz ederek hangi kullanıcıların hizmeti bırakma ihtimali olduğunu tahmin etmektir.

Kullanılan temel değişkenler:

Contract type (Sözleşme tipi)
Monthly charges (Aylık ücret)
Total charges (Toplam ücret)
Tenure (Müşteri süresi)
Payment method (Ödeme yöntemi)
Methodology / Yöntem

The project follows a complete machine learning workflow.

Proje aşağıdaki adımları içeren bir makine öğrenmesi süreci takip eder:

Veri temizleme ve ön işleme
Eksik verilerin işlenmesi (TotalCharges)
Kategorik değişkenlerin encode edilmesi
Train-test split işlemi
Feature scaling (StandardScaler)
Model eğitimi ve değerlendirme
Gerçek müşteri verisi ile test
Models Used / Kullanılan Modeller

The following machine learning models were implemented:

Bu projede aşağıdaki modeller kullanılmıştır:

Logistic Regression (baseline model)
Random Forest Classifier
Balanced Random Forest Classifier
XGBoost Classifier

Modeller karşılaştırmalı olarak değerlendirilmiştir.

Evaluation Metrics / Değerlendirme Metrikleri

Model performance was evaluated using:

Model performansı şu metriklerle ölçülmüştür:

Accuracy (Doğruluk)
Precision
Recall
F1-score
Confusion Matrix
Classification Report
Feature Importance Analysis / Özellik Analizi

Random Forest modeli kullanılarak feature importance analizi yapılmıştır.

En önemli faktörler:

Tenure (Müşteri süresi)
Monthly Charges (Aylık ücret)
Contract Type (Sözleşme tipi)
Payment Method (Ödeme yöntemi)
Prediction System / Tahmin Sistemi

The trained XGBoost model was tested with custom customer profiles.

Eğitilen XGBoost modeli, manuel oluşturulan müşteri profilleri üzerinde test edilmiştir.

Sistem şu çıktıları üretir:

Churn prediction (Kayıp / Kalacak)
Churn probability (Olasılık skoru)
Risk analizi
Technologies Used / Kullanılan Teknolojiler
Python
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Key Insights / Önemli Çıkarımlar
Short tenure customers are more likely to churn
→ Kısa süreli müşteriler daha yüksek churn riskine sahiptir
High monthly charges increase churn probability
→ Yüksek aylık ücret churn riskini artırır
Long-term contracts reduce churn risk
→ Uzun süreli sözleşmeler müşteri sadakatini artırır
Payment method affects customer behavior
→ Ödeme yöntemi müşteri davranışını etkiler
Future Improvements / Gelecek Geliştirmeler
Hyperparameter tuning (GridSearchCV)
Cross-validation
Model deployment (FastAPI)
Web dashboard interface
Production ML pipeline
Author / Yazar

Eren Oğan
Bilgisayar Mühendisliği Öğrencisi
Machine Learning & Artificial Intelligence Interest

Project Summary / Proje Özeti

This project demonstrates an end-to-end machine learning pipeline for customer churn prediction.

Bu proje, müşteri kaybı tahmini için uçtan uca bir makine öğrenmesi sürecini gösterm