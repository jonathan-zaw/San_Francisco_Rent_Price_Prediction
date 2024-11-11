# San_Francisco_Rent_Price_Prediction
Predicting rental prices in San Francisco using machine learning techniques. This project explores Ridge, Lasso, and ElasticNet regression models, leveraging real-world data to deliver actionable insights. Includes detailed preprocessing, model evaluation, and visualizations.




Project Overview

This project aims to predict rental prices in San Francisco using machine learning techniques. It involves data preprocessing, feature engineering, and model selection using Ridge, Lasso, and ElasticNet regression methods. The dataset includes features such as square footage, number of bedrooms, bathrooms, parking availability, and neighborhood information.

Key Features of the Project

Data Preprocessing: Standardization, handling categorical variables, and log transformation of target variable for normalization.
Model Comparison:
Ridge Regression: Achieved the best performance on test data.
Lasso Regression: Used for feature selection, providing insights into the most impactful variables.
ElasticNet: Combines Lasso and Ridge for balanced regularization.
Performance Metrics:
Evaluated using Mean Absolute Error (MAE) and R² on both cross-validation and test datasets.


Data Description

The dataset contains the following features:

sqft: Square footage of the property.
beds: Number of bedrooms.
bath: Number of bathrooms.
laundry: Type of laundry facility.
parking: Type of parking.
hood_district: Neighborhood district of the property.
Target: Log-transformed rental prices.
