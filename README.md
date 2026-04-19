# 📊 Bike Demand Forecasting in R

This project analyzes and forecasts hourly bike rental demand using both **classical time series models** and a **machine learning approach (XGBoost)**.

---

## 🎯 Objective

The goal of this project is to:

- Explore patterns in bike rental demand  
- Apply time series models (Holt-Winters, ARIMA, SARIMA)  
- Extend the analysis using machine learning (XGBoost)  
- Compare model performance using RMSE and MAE  

---

## 🧠 Methods Used

### 📈 Classical Time Series
- Holt-Winters (Exponential Smoothing)
- ARIMA
- SARIMA

### 🤖 Machine Learning
- XGBoost (using lag features and external variables)

---

## ⚙️ Features Used (for XGBoost)

- Lagged demand (previous hours, daily, weekly)
- Rolling statistics
- Weather variables:
  - Temperature
  - Humidity
  - Windspeed
  - Weather conditions
- Time-based features:
  - Hour
  - Weekday
  - Month

---



## 🛠️ Tools & Libraries

- R
- forecast
- xgboost
- dplyr
- ggplot2
- readxl
