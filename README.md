# 🛒 Sales Forecasting for Grocery Retailers Using Random Forest (Python)

This repository contains a sales forecasting project for my *Programming in Python for Business Analytics* module. The project builds a forecasting model for a South American grocery retailer to address the challenge of over- and under-stocking perishable goods across 54 stores and 33 product types.

📌 **Goal**: Predict daily sales for each product in each store for the period of **July 31 – August 15, 2017** using machine learning (Random Forest Regressor).

📋 **Reflections**: a Random Forest model + structured feature engineering = a strong baseline for forecasting sales in high-dimensional retail datasets. With more time, future improvements could include:
- Hyperparameter tuning via GridSearchCV
- Trying XGBoost or hybrid models
- 	Using time-series-specific techniques (e.g., ARIMA, Prophet) 

---

In this project, we:
- Built a Random Forest regression model to forecast sales
- Created a feature set using historical sales and special offer promotions (10-day lag)
- Evaluated model performance using MSE, MAE, and R²
- Visualised actual vs. predicted sales trends

----

The report provides an in-depth look at:
- Business context
- Data engineering
- Model tuning
- Evaluation metrics
- Visual analysis
- Strategic implications
