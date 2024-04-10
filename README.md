
## Stock Price Prediction Project
### Project Overview
This project aims to predict stock prices using a Stacked Long Short-Term Memory (LSTM) model. We focus on the Apple Inc. (AAPL) stock, using historical stock price data to train our model. The project encompasses data collection, preprocessing, model creation, prediction, and visualization phases to showcase the potential of LSTM in financial forecasting.

### Key Features:
Data Collection: Fetching AAPL stock data via API.
Preprocessing: Preparing the dataset for training and testing.
Model Creation: Building a Stacked LSTM model to learn from the stock price data.
Prediction & Visualization: Predicting stock prices and visualizing the results.

### Tools and Technologies
Python
Pandas for data manipulation.
Matplotlib for data visualization.
TensorFlow and Keras for building the LSTM model.
Scikit-learn for data preprocessing.

### Project Structure
Data Collection: Utilizing pandas_datareader and requests to gather AAPL stock data.
Data Preprocessing: Splitting the dataset into training and testing sets, and applying MinMax scaling.
Stacked LSTM Model: Designing a LSTM model suited for time series forecasting.
Prediction: Implementing the model to predict future stock prices and comparing predictions with actual prices.
Future Prediction: Extending the model to predict stock prices for an additional 30 days beyond the dataset.