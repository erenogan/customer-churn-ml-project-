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
High monthly charges increase churn probability
Long-term contracts reduce churn risk
Payment method affects customer behavior
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

Bu proje, müşteri kaybı tahmini için uçtan uca bir makine öğrenmesi sürecini göstermektedir.
