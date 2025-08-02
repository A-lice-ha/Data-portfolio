# 🌞 Solar Irradiance Forecasting using NASA POWER API

This project builds a modular R pipeline to forecast solar energy potential using daily solar irradiance data from 2013–2023. Five forecasting models were compared to identify the most accurate approach.

## 🛠️ Tools Used
- R: tidyverse, forecast, caret, xgboost
- NASA POWER API
- ggplot2, dplyr

## 📈 Workflow
1. Data extraction from NASA POWER API
2. Cleaning, feature engineering (lags, rolling stats)
3. Model training: Linear Regression, XGBoost, GAM, SARIMA, Random Forest
4. Evaluation using RMSE and MAE
5. Visualization of future predictions

## 🔍 Sample Output
*(Add graphs and plots here later)*

## 📂 Files
- `/scripts/forecasting_models.R`: Full forecasting pipeline
- `/plots/`: Forecast visualizations
