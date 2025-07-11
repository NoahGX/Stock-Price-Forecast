# Stock Price Forecast

## Overview
The purpose of this Jupyter Notebook is to anayze stock prices using historical market data. It employs deep learning techniques, specifically LSTM Long Short-Term Memory (LSTM) networks, to forecast future prices based on past trends. TensorFlow (via its high-level API, Keras) is used to define and build the LSTM neural network model.

## Features
- **Data Collection**: Fetch historical stock price data using the `yfinance` library.
- **Data Exploration and Preprocessing**: Explore and prepare data for model training, including normalization and data splitting.
- **Model Building**: Construct an LSTM-based model to predict stock prices.
- **Evaluation**: Evaluate the model's performance using metrics like RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).

## Usage
- Ensure all prerequisites are installed.
- Open `stockprice.ipynb` in Jupyter Notebook or JupyterLab.
- Run the cells sequentially to perform data collection, preprocessing, model training, and evaluation.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `numpy`, `pandas`, `yfinance`, `seaborn`, `matplotlib`, `tensorflow`, `keras`, `sklearn`

## Input
- **Stock Symbols**: A list of stock symbols for which predictions are desired (e.g., AMZN, GOOG, MSFT, TSLA).
- **Date Range**: Date range for historical data retrieval.

## Output
- Predicted stock prices for the upcoming days.
- Visualization of actual vs. predicted prices and error metrics.

## Notes
- Accuracy of predictions may vary based on market volatility and the model's limitations.
- The model should be retrained periodically to incorporate the latest data, as well as being continually updated with the latest techniques.
- This model requires various modifications for production and deployment.
