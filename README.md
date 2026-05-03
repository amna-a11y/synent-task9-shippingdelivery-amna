# Shipping Delivery Prediction System

## Problem Statement

Late deliveries in logistics impact customer satisfaction and business efficiency. This project predicts whether a shipment will be delivered on time or late using machine learning models.

## Dataset Details

The dataset includes shipment-related features such as warehouse block, mode of shipment, product importance, customer care calls, customer rating, cost of product, discount offered, weight in grams, gender, and the target variable (late delivery: 0 = on time, 1 = late).

## Approach

Data preprocessing, encoding categorical variables, feature engineering, handling class imbalance using SMOTE, train-test split (80/20), and model training using Logistic Regression, Decision Tree, and Random Forest. Best model selected using ROC-AUC score and deployed using Streamlit.

## Results

Random Forest performed best among all models. The system successfully predicts whether a shipment will be delivered on time or late.
*
