# Terrorist Attacks Analysis and Forecasting

## Project Overview

This project aims to analyze historical data on terrorist attacks and forecast future trends using time series analysis. The project utilizes the ARIMA model for forecasting and provides insights into the distribution and frequency of terrorist attacks globally.

## Data

- The dataset contains historical records of terrorist attacks, including details such as the country, year, and number of attacks.
- Non-country entities and redundant entries were removed during data cleaning.

## Steps Undertaken

1. **Data Cleaning**:
   - Removed non-country entries (e.g., "WORLD," "USSR").
   - Handled missing values and corrected data types.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of terrorist attacks by country and year using a heatmap.
   - Grouped data into 5-year intervals and plotted the distribution over time.

3. **Modeling**:
   - Applied the ARIMA model to forecast terrorist attacks for the next 10 years.
   - Trained the model on historical data and generated future predictions.

4. **Model Evaluation**:
   - Evaluated the model's performance by comparing forecasted values with historical data.

