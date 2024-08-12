# Stock_price_LSTM_Logistic
This document describes a project focused on predicting stock prices using machine learning techniques, specifically Long Short-Term Memory (LSTM) neural networks. The project is part of a capstone project for the Udacity Machine Learning Nanodegree and was conducted by Rajat Dhyani.

Project Overview:
The primary goal of the project is to predict the closing price of stocks, particularly for the S&P 500, using historical stock prices and trading volumes. LSTM networks, a type of recurrent neural network (RNN), were chosen for this task because of their ability to learn from time-series data, capturing long-term dependencies.

Problem Statement:
The project aims to accurately predict the future closing price of a stock for a given period using LSTM models. The challenge is to develop a model that can make predictions based on historical data, potentially offering insights into future stock market trends.

Data and Analysis:
The dataset used in this project includes historical stock prices for Alphabet Inc. (Google) from January 1, 2005, to June 20, 2017. The dataset contains features like opening, high, low, closing prices, and trading volume. The analysis suggests that the high and low prices are less important for predicting closing prices, so these features were removed during preprocessing.

Methodology:
The data preprocessing involved normalizing the data and splitting it into training and testing sets. The project implemented a benchmark model using Linear Regression and then compared it to an LSTM model built using the Keras library. The LSTM model was optimized by tuning various parameters, including the number of layers, nodes, and epochs.

Results:
The project's success was measured using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). The LSTM model's performance was compared to the Linear Regression model, showing the advantages of using deep learning techniques for time-series prediction.

Conclusion:
The project concludes that LSTM networks are effective for predicting stock prices, providing better accuracy than traditional linear regression models. The analysis also highlights the importance of careful data preprocessing and parameter tuning in building an effective predictive model.

This project demonstrates the potential of using deep learning models, specifically LSTM networks, for financial forecasting, showing their applicability in real-world scenarios like stock price prediction.
