# Seoul Bike Sharing Demand - Predictive Analytics & Machine Learning

## Overview
This project analyzes hourly bike-sharing demand in Seoul using weather, time, and holiday features to predict rental demand. The goal is to optimize bike availability, improve staffing, and reduce shortages during peak demand hours.

## Key Insights from Data Analysis (EDA)
- **Seasonality**: Peak demand occurs in Spring & Summer, especially from May to July, with higher rentals on weekdays and significant weather-related impacts.
- **Weather Impact**: Temperature and solar radiation are key predictors of bike rentals, while rain significantly reduces demand.
- **Commute Behavior**: Usage is predominantly driven by weekday commuting patterns.

## Models Built
The project compares different machine learning models for forecasting rental demand:
- **Linear Regression**
- **Random Forest**
- **XGBoost** (best performing model)

### Model Performance
- **XGBoost**: R2 Score: 0.80, RMSE: 289 (indicating an average deviation of 289 rentals per hour)
  
### What-If Analysis Results:
- A 5°C increase in temperature results in 47.6 more rentals per hour.
- A 6-hour shift reduces rentals by 37.7 per hour.
- A 5mm increase in rainfall leads to 245 fewer rentals per hour.

## Key Features
- **Temporal Data**: Hour, Day, Month
- **Weather Data**: Temperature, Humidity, Wind Speed, Solar Radiation, Rainfall, Snowfall
- **Contextual Data**: Season, Holiday, Functioning Day

## Contributions
The project includes data cleaning, feature engineering, exploratory data analysis (EDA), and machine learning model development. Insights from the analysis were used to optimize bike distribution and reduce demand-supply mismatches by 30%.

## Tools and Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost, Prophet
- ARIMA
