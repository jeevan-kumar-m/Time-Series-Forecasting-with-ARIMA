
# Time Series Forecasting with ARIMA and SARIMA Models

This README provides an overview of the Time Series Forecasting project using ARIMA and SARIMA models.

 Objective

The objective of this project is to forecast future stock prices of Google (symbol: GOOG) using Time Series Forecasting techniques.

 Steps Involved

1. Data Retrieval: 
   - Data for the GOOG stock was retrieved from Yahoo Finance using the `yfinance` library.
   - The data includes the date, open, high, low, close, adjusted close prices, and volume.

2. Data Preparation:
   - The data was cleaned and formatted to include only the necessary columns (date and close prices).

3. Exploratory Data Analysis:
   - Visualization of the closing stock prices of Google was performed using matplotlib.

4. Modeling:
   - ARIMA Model: 
     - An ARIMA model was initially attempted to forecast future stock prices. However, it was observed that the dataset exhibits seasonality, rendering the ARIMA model ineffective.
   - SARIMA Model: 
     - As the data showed seasonality, a Seasonal ARIMA (SARIMA) model was employed for better forecasting accuracy.

5. Model Evaluation:
   - The SARIMA model was evaluated for its performance in predicting future stock prices.

6. Results:
   - The predictions from the SARIMA model were compared with actual stock prices to assess the model's accuracy.

7. Conclusion:
   - The project concludes with insights into the effectiveness of the SARIMA model for forecasting stock prices and its potential applications.

Summary
ARIMA stands for Autoregressive Integrated Moving Average. It is an algorithm used for forecasting Time Series Data. If the data is stationary, we need to use ARIMA, if the data is seasonal, we need to use Seasonal ARIMA (SARIMA). I hope you liked this article about Time Series Forecasting with ARIMA using Python. Feel free to ask valuable questions in the comments section below.
