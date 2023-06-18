# Financial-Analysis-of-Stock-Prices

**Introduction**

This repository contains a comprehensive analysis and prediction model for Yamaha Financial GE stock prices. Using Long Short-Term Memory (LSTM) networks, a type of recurrent neural network, we've developed a system that provides accurate forecasting for stock prices, offering valuable insights for investors and financial analysts alike.

**Preprocessing**

Data preprocessing plays a crucial role in building the prediction model. The dataset was imported from a CSV file, featuring columns such as 'Open', 'High', 'Low', 'Close', and 'Adj Close'. Any null values were identified and addressed to ensure the data's integrity. We then scaled the data using Standard Scaler for efficient model training.

**Exploratory Data Analysis (EDA)**

EDA involved several statistical and visual analyses, allowing us to understand the data better. We examined the distribution of trading volumes, conducted autocorrelation analysis, and established moving averages. Additionally, we visualized the daily returns distribution to understand the stock's volatility.

**Model**

Our model comprises multiple LSTM layers with a Dropout layer to prevent overfitting. We compiled it with the Adam optimizer and mean squared error as the loss function. The model summary and training progression are visualized in the code.

**Prediction and Visualization**

Using the developed model, we forecasted stock prices for future dates, accounting for business days. The results were inverse transformed to match the original data scale and visualized for comparison against the actual stock prices.

**Conclusion**

Through this project, we showcased the power of LSTM networks in predicting financial time series data. Our approach provides investors and financial analysts with a reliable tool to understand and predict Yamaha Financial GE's future performance, helping them make well-informed decisions.
