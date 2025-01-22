# Bike Sharing Demand Forecasting  

## Overview  
This project involves building a time-series forecasting model using the **Prophet library** to predict daily bike-sharing demand. By analyzing historical data and incorporating external factors like weather conditions and temporal patterns, the project aims to provide actionable insights for efficient resource allocation.  

## Objectives  
- Predict daily bike-sharing demand with high accuracy.  
- Identify key factors influencing bike usage patterns, such as weather and seasonal trends.  
- Provide operational insights to optimize bike-sharing resources and reduce underutilization.  

## Tools and Technologies  
- **Programming Language:** Python  
- **Libraries:** Pandas, Matplotlib, Prophet, NumPy, Scikit-learn  

## Dataset  
The dataset used includes:  
1. **Historical demand data:** Daily records of bike-sharing usage.  
2. **Weather data:** Temperature, humidity, and other weather-related variables.  
3. **Temporal features:** Holiday information and weekday/weekend indicators.  

## Methodology  
1. **Data Cleaning and Preprocessing**  
   - Handled missing values and outliers.  
   - Engineered features such as lagged variables, holidays, and seasonal components.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized historical trends and seasonal patterns using **Matplotlib**.  
   - Analyzed correlations between weather variables and bike demand.  

3. **Modeling**  
   - Used the **Prophet library** to build a time-series forecasting model.  
   - Incorporated external regressors (e.g., temperature, humidity) to enhance model accuracy.  
   - Tuned hyperparameters such as changepoints and seasonality to improve predictions.  

4. **Evaluation**  
   - Conducted cross-validation to evaluate model stability across different time periods.  
   - Achieved **RMSE: 1266** and **MAPE: 16%**.  

5. **Insights and Recommendations**  
   - Identified peak usage periods and low-demand days.  
   - Recommended strategies for resource optimization based on demand patterns.  

## Key Results  
- **Forecast Accuracy:** RMSE of 1266 and MAPE of 16%.  
- **Feature Importance:** Weather variables (e.g., temperature and humidity) significantly impact demand.  
- **Operational Insights:** Clear seasonal trends and demand spikes on weekends and holidays.  
