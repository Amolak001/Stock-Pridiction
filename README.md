# Stock Price Prediction App
This repository contains a comprehensive Stock Price Prediction Application developed with Python and Streamlit, designed to forecast future stock prices for major tech companies like Alphabet Inc. (GOOG), Microsoft Corporation (MSFT), and Apple Inc. (AAPL). Leveraging an LSTM (Long Short-Term Memory) model, the app offers interactive stock predictions and visualizations to assist with financial insights and decision-making.

## Overview
This app provides an intuitive interface for forecasting stock prices for the next 15 days. Users can view historical stock trends with detailed price information—including high, low, open, and close prices—up to the current date. The app's goal is to offer a streamlined tool for exploring stock trends, conducting exploratory data analysis, and generating future forecasts to aid in investment planning.

## Key Features
1. 15-Day Price Prediction: Users can generate and view a 15-day forecast for selected stocks, providing insight into possible short-term price trends.
2. Historical Data Visualization: Displays detailed historical data with high, low, open, and close prices, giving users a clear view of past stock performance.
3. Interactive Interface: Built with Streamlit, the app is easy to use and allows users to switch between different stocks and see forecasts instantly.
4. LSTM-based Forecasting: Utilizes a deep learning model designed to handle time-series data, capturing the sequential patterns and dependencies in stock prices.
5. Performance Metrics: Includes metrics like Root Mean Squared Error (RMSE) to gauge the prediction accuracy and reliability.

## Repository Contents
1. lstm_model.py :
   Contains the implementation of the LSTM model used for generating stock price predictions. It includes data preprocessing, model setup, training, and testing functions to handle stock data.

3. app.py :
   The main application script, powered by Streamlit, integrates the model with an interactive front end. Users can select stocks, visualize past trends with high/low/open/close prices, view 15-day forecasts, and observe model evaluation metrics.

5. requirements.txt :
   A list of dependencies required to run the application. This file allows users to easily set up the required environment by running pip install -r requirements.txt.

## Deployed App
🌐 Try the Deployed App: https://stock-pridiction.streamlit.app/
