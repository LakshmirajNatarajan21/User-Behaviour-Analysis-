# Facilitating Customers Towards Product Subscription in Fin-Tech Applications Through Behavioral Analysis


## Overview
This repository contains the code, datasets, and documentation for my MSc Research Project at the National College of Ireland. The project focuses on using behavioral analysis and machine learning to predict customer subscriptions for premium services in a financial technology (FinTech) application.

## Objective
To analyze user interaction metrics in a FinTech app and develop a predictive model that identifies potential premium subscribers, helping optimize marketing strategies and reduce customer acquisition costs.

## Key Features
Data Preprocessing: Comprehensive cleaning, feature engineering, and transformation of user interaction data.
Model Development: Built and tested multiple neural network models to improve prediction accuracy.
Techniques Used: Regularization, K-Fold Cross-Validation, and Ensemble Learning.
Insights: Identified key user behavior patterns and financial constraints impacting subscription likelihood.

## Tools & Technologies
Programming Language: Python
Libraries: TensorFlow, Keras, Pandas, NumPy, Seaborn, Matplotlib
Databases: MongoDB, MySQL
Development Environment: Google Colab

## Key Outcomes of the Research
Predicting Customer Subscription Behavior:

The study successfully developed a machine learning model using a Neural Network to predict which users are more likely to subscribe to premium fintech services.
The best-performing model achieved 78.22% accuracy, indicating that behavioral data is a strong predictor of subscription intent.
Optimal Model for Prediction:

Four different model variations were tested:
Baseline Neural Network Model – Accuracy: 77.59%
Neural Network with Regularization – Accuracy: 77.25%
Neural Network with K-Fold Cross-Validation – Accuracy: 77.78%
Neural Network with Ensemble Learning – Best Accuracy: 78.22%
The Ensemble Learning model provided the best balance between accuracy and generalization.
Key Behavioral Insights:

User Engagement & Subscription:
Users between the ages of 19-25 showed a higher subscription rate.
Users who interacted with premium features during their free trial were more likely to subscribe.
Time-Based User Behavior:
Users typically engaged with the application between 10 AM - 6 PM, with lower activity after 8 PM.
Feature Importance:
Screens related to financial transactions, credit monitoring, and savings plans had a strong correlation with premium subscriptions.
Customer Segmentation & Marketing Strategy:

Segmenting non-subscribers based on financial constraints and engagement:
Users who engaged highly but had financial limitations could be targeted with flexible payment plans.
Optimizing marketing strategy:
By identifying the most engaged users, fintech firms can reduce advertising costs and increase ROI on marketing efforts by focusing on high-potential customers.
Business Implications & Future Research:

The model can help fintech firms optimize their premium subscription promotions by focusing on the right audience.
Future improvements could include:
Incorporating real-time behavior tracking.
Adding more features (e.g., spending patterns, transaction frequency).
Improving model scalability and interpretability.
