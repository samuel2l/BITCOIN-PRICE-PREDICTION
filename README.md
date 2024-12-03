# Bitcoin Price Prediction

A machine learning project aimed at predicting Bitcoin prices using various algorithms, including Random Forest, LSTM (Long Short-Term Memory), and Linear Regression. This project explores and compares the performance of these models on historical Bitcoin price data.
Involved using prices from previous 60 days(lagged features) to predict the price for the next day

## Project Overview

Cryptocurrencies, like Bitcoin, are known for their volatility, making price prediction a challenging task. This project aims to analyze historical price trends and apply machine learning algorithms to predict future prices. The models were trained and tested on real-world data sourced from Yahoo Finance.

## Dataset

The historical Bitcoin price dataset was obtained from Yahoo Finance. You can access the dataset [here](https://finance.yahoo.com/quote/BTC-USD/history/).

## Algorithms Used

1. **Random Forest**  
   - A robust ensemble learning method that leverages multiple decision trees for prediction.
2. **LSTM (Long Short-Term Memory)**  
   - A type of recurrent neural network (RNN) suitable for sequential data like time series.
3. **Linear Regression**  
   - A simple regression technique to establish a linear relationship between features and the target variable.

## Features

- **Data Preprocessing**: Handling missing values, normalizing data, and feature engineering.
- **Model Training and Testing**: Splitting data into training and test sets and tuning model parameters.
- **Evaluation Metrics**: Models are evaluated using metrics such as Mean Squared Error (MSE) and R-squared.
- **Visualization**: Graphical representation of actual vs. predicted prices for better insights.



