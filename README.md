# Stock-Prediction-using-RNN
Stock Prediction
Project Overview: This project focuses on time series forecasting using recurrent neural network (RNN) models, 
specifically SimpleRNN, LSTM, and GRU models. The goal of the project is to predict the closing stock prices of Amazon (AMZN) based 
on historical stock data. The project begins by importing the necessary libraries such as numpy, pandas, matplotlib, and TensorFlow. 
It also includes the required functions and classes for data preprocessing, model training, evaluation, and visualization. 
The data is loaded from a CSV file ('AMZN.csv') and preprocessed to extract the desired timeframe. 
The data is then split into training and testing sets. Various data exploration and visualization techniques are employed to gain insights 
into the dataset. Next, different RNN models, including SimpleRNN, LSTM, and GRU, are implemented using the TensorFlow Keras API. 
These models are trained on the training data using the provided functions for model training. 
The training process involves setting the number of epochs, applying early stopping to prevent overfitting, 
and optimizing the model's performance using loss functions and metrics. 
The training progress is monitored and visualized through plots of the training and validation loss values. 
After training, the models are evaluated using different evaluation metrics such as Mean Absolute Error (MAE), 
Mean Absolute Percentage Error (MAPE), and Median Absolute Percentage Error (MDAPE). 
These metrics are calculated by comparing the predicted values with the actual test values. 
The predictions made by the models are then visualized using line charts, allowing a visual comparison between the predicted and 
actual values. The project includes functions to plot line charts showing the predicted values, training data, and testing data. 
Finally, the models are used to make future price predictions based on the most recent data. 
The predicted prices are compared with the last known price, and the percentage change is calculated to provide insights into the model's 
performance. Overall, this project demonstrates the implementation and evaluation of different RNN models for time series forecasting 
of Amazon stock prices. It covers data preprocessing, model training, evaluation, visualization, and prediction steps to provide a 
comprehensive analysis of stock price forecasting.
