Overview

This repository contains two major projects completed as part of a six-month internship in the field of Data Science and Machine Learning. Both projects demonstrate end-to-end workflows, including data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), model building, and evaluation.

The two domains covered are Cybersecurity (suspicious traffic detection) and Healthcare (life expectancy prediction). Together, they showcase the application of ML in both classification and regression problems.

🚀 Project 1: Cybersecurity – Suspicious Web Threat Interactions

This project focuses on analyzing web traffic data from AWS CloudWatch to detect suspicious and malicious interactions. The dataset includes details such as IP addresses, ports, bytes transmitted, country codes, and detection labels.

Key Work Done:

Cleaned and preprocessed the raw data (duplicates, missing values, timestamp conversions).

Engineered features like session duration, average packet size, throughput.

Conducted EDA: bytes distribution, protocol/port usage, country-wise traffic, time-series analysis, correlation heatmap, and a network graph.

Applied Anomaly Detection: Isolation Forest and Local Outlier Factor.

Built Classification Models: RandomForest, Multi-Layer Perceptron (MLP), and Conv1D Neural Networks.

Evaluated using accuracy, precision, recall, F1-score, ROC-AUC.

Achieved 90%+ accuracy with RandomForest and saved trained models for deployment readiness.

👉 Notebook: Cybersecurity_Project.ipynb

🚀 Project 2: Life Expectancy Analysis

This project applies machine learning to predict life expectancy across countries based on socio-economic and health indicators such as GDP, schooling, alcohol consumption, and healthcare expenditure.

Key Work Done:

Cleaned the dataset (missing values handled with mean imputation, outliers treated using IQR).

Performed EDA:

Life expectancy distribution

Correlation heatmap

Trends across years

Comparisons between developed and developing countries

Preprocessed data with Label Encoding and Standard Scaling.

Implemented regression models: RandomForest, ExtraTrees, GradientBoosting, XGBoost.

Compared models using RMSE and R² metrics.

Performed Cross Validation on XGBoost for robustness.

Final model (XGBoost) achieved strong performance with low RMSE and high R².
