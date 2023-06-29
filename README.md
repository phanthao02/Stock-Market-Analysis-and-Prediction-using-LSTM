# Stock-Market-Analysis-and-Prediction-using-LSTM

This repository contains code for preprocessing, exploratory data analysis (EDA), and prediction of stock market closing prices using the Long Short-Term Memory (LSTM) model. The following steps were performed to accomplish this:

## Data Processing
The raw data was preprocessed to ensure it is suitable for analysis and prediction. This included changing the data types of features to their appropriate formats and adding customized attributes to enhance the dataset.

## Exploratory Data Analysis (EDA)
EDA was conducted on various aspects of the stock market using the processed data. The following key aspects were analyzed using mainly the matplotlib library:

* Closing Price: Visualizations were created to understand the trends and patterns in the closing prices of stocks
* Average Daily Trading Volume: Analysis was performed to gain insights into the trading volume and identify any significant changes or anomalies
* Simple Moving Average: The moving average was calculated and visualized to identify trends and support decision-making
* Daily Stock Return: The daily returns of stocks were analyzed to assess their volatility and potential risks

## LSTM Model for Stock Price Prediction
A LSTM model was built to predict future closing stock prices based on the previous 90 days' performance history. The LSTM model is a type of recurrent neural network (RNN) that is well-suited for time series analysis. It can capture long-term dependencies and patterns in the data, making it effective for stock price prediction.
