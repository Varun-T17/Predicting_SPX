# Predicting_SPX_500

Using an ARIMA model and various variables, I am trying to predict the price of the S&P 500 by the end of 2024.

I have modelled the price using the ARIMA model. For input I used nominal GDP data, Interest Rates, WTI (Crude Oil Spot price) and World governance index indicators for the US to predict the S&P’s price next year. 
 
ARIMA (AutoRegressive Integrated Moving Average) models can perform well in forecasting stock market data for many reasons: 
 
•	Time Series Analysis: Data is often represented as a time series, where observations are collected continuously over time, annually in my case, ARIMA models are specifically designed to analyze time series data. 
 
•	Trend and seasonality capture: The ARIMA model can capture the trend and seasonality of stock prices. They are able to model short-term volatility and long-term trends in data, which is important for predicting stock market trends. 
 
•	Changes in accuracy: ARIMA models require consistency in the data. By differentiating time series data (the integrated version of ARIMA), non-volatile data can be converted into static ones. Position simplifies sampling and makes it easier to capture underlying patterns. 
 
•	Lagging relationships: ARIMA models have auto-regressive (AR) and moving average (MA) components, allowing them to capture dependencies and correlations between past and present observations This is especially important in savings often based on past prices. 
 
•	Model interpretability: ARIMA models provide interpretive coefficients, which can be valuable in understanding the impact of lagged price and seasonal patterns on stock prices. 
 
My model predicts the price of S&P 500 to be 4652 by the end of the next year. 
 
I have attached the input data as well as a jupyter notebook with the code.
