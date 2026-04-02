House Price Prediction - End-to-End Machine Learning Project
Project Overview

This project is an end-to-end machine learning solution designed to predict house prices based on various features such as area, number of bedrooms, bathrooms, and location. It demonstrates the complete ML workflow from data preprocessing to model deployment readiness.

The goal is to simulate a real-world business scenario where accurate property valuation helps buyers, sellers, and real estate platforms make informed decisions.

 Objectives
Build a complete ML pipeline
Compare multiple machine learning algorithms
Perform feature engineering and preprocessing
Evaluate models using multiple metrics
Interpret model predictions
Prepare the system for deployment
📂 Dataset
File: house_prices.csv
Rows: ~300
Features include:
Area (sqft)
Bedrooms
Bathrooms
Age of property
Location
Property type
Target Variable: Price
Machine Learning Workflow
Data Preprocessing
Handling missing values
Encoding categorical variables
Feature scaling using StandardScaler
Train-test split to prevent data leakage
Feature Engineering
Created meaningful derived features
Improved model performance through better representation of data
Models Implemented
Linear Regression
Random Forest Regressor

Model Evaluation

Models are evaluated using:

Mean Absolute Error (MAE)
R² Score
Cross-validation (recommended improvement)
Model Selection
Best-performing model selected based on evaluation metrics
Random Forest generally performs best due to handling non-linearity
Model Persistence
Model saved using pickle for future use:
models/model.pkl
Input Validation

Custom validation logic implemented to ensure:

Correct data types
Valid ranges
Missing field handling
Sample Results
Metric	Value
MAE	₹4–5 Lakhs (approx)
R² Score	~0.80–0.85
