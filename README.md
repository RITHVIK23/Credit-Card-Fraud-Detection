STAT654-CreditCard_Fraud_Detection
This project aims to detect fraudulent credit card transactions using machine learning algorithms. The dataset used in this project is sourced from Kaggle and can be found at Kaggle - Credit Card Fraud Detection Dataset.

Dataset Overview
The dataset contains transactions made by credit cards in September 2013 by European cardholders. It consists of features such as transaction amount, time, and anonymized numerical features obtained through Principal Component Analysis (PCA) due to privacy concerns.

Feature Engineering
Prior to model training, several preprocessing steps were performed on the dataset:

Scaling: The transaction amount feature was scaled using standard scaling to bring all features to the same scale. Time Transformation: The time feature, representing the seconds elapsed between each transaction and the first transaction in the dataset, was transformed into day and hour features for better interpretation and analysis.

Exploratory Data Analysis (EDA)
A comprehensive analysis of the dataset was conducted using various EDA techniques, including:

Visualization of transaction amounts over time.
Distribution of fraudulent vs. non-fraudulent transactions.
Correlation analysis between features.
Detection of outliers and anomalies.
Machine Learning Models
Seven machine learning models were trained and evaluated on the transformed dataset:

Logistic Regression
Naive Bayes
Support Vector Machines (SVM)
Decision Tree
Random Forest
Gradient Boosting
XGBoost
Sampling Techniques
To address the issue of class imbalance in the dataset, various sampling techniques were employed, including:

8 Random Oversampling

Random Undersampling
Synthetic Minority Oversampling Technique (SMOTE)
AdaSYN
Conclusion
This project provides a comprehensive approach to credit card fraud detection, starting from data preprocessing and feature engineering to model training and evaluation. By comparing the performance of different machine learning algorithms and sampling techniques, the aim is to identify the most effective approach for detecting fraudulent transactions in real-world scenarios.
