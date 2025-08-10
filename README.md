🛒 Walmart Sales Forecasting - Time Series Regression
This project was completed as part of Elevvo’s Data Science program (Task 7) and focuses on forecasting weekly sales for Walmart stores using time series regression models.

📌 Project Overview
The goal of this project is to build predictive models that forecast future sales based on historical data using engineered time-based features and machine learning algorithms.

📂 Dataset
Source: Walmart Sales Forecasting Dataset (Kaggle)

Files Used:

train.csv – Historical weekly sales data

test.csv – Future dates for prediction

features.csv – Economic and promotional indicators

stores.csv – Store metadata

🔧 Techniques & Tools
Feature Engineering

Extracted date-based features: Day, Week, Month, Year

Created lag and rolling window features: Sales_Lag_1, Rolling_Mean_4

Categorical encoding of features like Type, IsHoliday

Models Used

🧠 XGBoost Regressor

🌲 Random Forest Regressor

Validation Strategy

Time-aware split (before and after 2012-01-01)

Evaluation metrics: MSE, RMSE, R² Score

📈 Results & Insights
Visualized actual vs. predicted sales for validation data

Exported predictions for the test set

Identified most important features impacting forecast performance

📊 Tools & Libraries
Python | Pandas | Matplotlib | Scikit-learn | XGBoost

📝 Output Files
Test_Result.csv – Predictions using XGBoost

test_predictions.csv – Predictions using Random Forest
