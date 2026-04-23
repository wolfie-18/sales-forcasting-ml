# sales-forcasting-ml
# 🛒 Retail Sales Forecasting App

#Overview

Retail businesses often struggle with demand fluctuations, leading to overstocking or stockouts.
This project builds a **Sales Forecasting System** that predicts future sales using historical data and machine learning.

The goal is to help retailers make **data-driven inventory decisions** and improve profitability.

# Features

*  Forecast daily/weekly sales
*  Machine Learning model (XGBoost)
*  Time-based feature engineering (lag & rolling features)
*  Evaluation using RMSE & MAPE
*  Visualization of Actual vs Predicted sales
*  Interactive Streamlit web app

# Problem Statement

Retail chains face:

* Demand uncertainty
* Overstocking losses
* Stockout risks

This project solves it by:

* Predicting future sales
* Capturing seasonality and trends
* Using historical patterns for accurate forecasting

#Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib
# Dataset

The dataset includes:

* Date
* Store/Product information
* Sales values

Additional engineered features:

* Lag features (previous day/week sales)
* Rolling averages
* Date-based features (day, month, weekday)

# ⚙️ Feature Engineering

Key features used:

* `lag_1` → Previous day sales
* `lag_7` → Previous week sales
* `rolling_mean_7` → Weekly trend
* Day, Month, Day of Week

These features help capture:

* Trends
* Seasonality
* Temporal dependencies

#Model Used

### XGBoost Regressor

* Handles non-linear patterns
* Works well with tabular data
* Provides feature importance

# Evaluation Metrics

* **RMSE (Root Mean Squared Error)** → Measures prediction error
* **MAPE (Mean Absolute Percentage Error)** → Business-friendly accuracy (%)

# Results

* Model successfully captures sales trends
* Lag features significantly improve predictions
* Rolling averages stabilize forecasts

# Key Insights

* Recent sales strongly influence future demand
* Weekly patterns (weekends vs weekdays) affect sales
* Rolling averages help smooth fluctuations


# Future Improvements

* Add weather data integration
* Use advanced time series models (Prophet/SARIMA)
* Multi-store forecasting
* Real-time dashboard

# Conclusion

This project demonstrates how machine learning can be applied to solve real-world retail problems by forecasting demand and optimizing inventory decisions.

# Author

Kunal Singh
