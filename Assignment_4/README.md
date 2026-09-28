# Assignment 4 – LSTM-Based Time-Series Forecasting

## Problem Statement

Develop an LSTM-based model for time-series forecasting using stock price, weather, or sales datasets.

## Objective

To develop a Long Short-Term Memory (LSTM) neural network for time-series forecasting and understand how LSTM can learn patterns and dependencies from sequential data.

## Dataset

Historical stock price data is used for forecasting.

## Implementation

The implementation includes:

- Collection and preprocessing of stock price data
- Data normalization using MinMaxScaler
- Creation of sequential input data
- Splitting the dataset into training and testing sets
- Development of an LSTM-based neural network
- Model training and validation
- Prediction of stock prices
- Comparison of actual and predicted values

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Model

The LSTM model learns temporal dependencies from previous stock prices and predicts the next stock price.

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Result

The performance of the LSTM model is evaluated by comparing the predicted stock prices with the actual stock prices using numerical evaluation metrics and visualization.

## Conclusion

LSTM is suitable for time-series forecasting because it can retain important information from previous time steps and learn long-term dependencies in sequential data.
