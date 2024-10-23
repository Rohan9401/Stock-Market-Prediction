# Stock-Market-Prediction

Problem Statement:

• Predict the NIFTY50 stock market closing prices that will be beneficial in making crucial financial decisions by investors, traders and financial institutions. 

Approach:

• Exploratory Data Analysis was performed for better understanding of the data.
• Stationarity tests like Augmented Dickey-Fuller Test was used to assess the stationary of the time series data.
• A neural network (LSTM) was trained and tuned using Random Search to forecast the closing prices of the stock market.
• The model loss over epochs was visualized and the train loss and validation loss was decreasing over time suggesting the model learnt well.
• The model's performance was evaluated using MAE, RMSE, and R² scores.
• The stock market closing prices was forecasted and visualized for the next 60 days.

Tools and Techniques Used: Python (Programming Language) · Pandas (Software) · TensorFlow · Keras · Deep Learning · Time Series Forecasting · NumPy · Matplotlib · Seaborn
