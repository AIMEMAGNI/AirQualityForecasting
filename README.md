# Air Quality Forecasting

## Overview

This project aims to forecast PM2.5 (Particulate Matter) levels using Long Short-Term Memory (LSTM) networks. PM2.5 levels are a critical indicator of air quality, and this model uses historical air quality and weather data to predict future concentrations.

## Files

- **air_quality_forecasting.ipynb**: Jupyter notebook containing data analysis, model training, and evaluation steps.

## Model

The model is based on **LSTM** (Long Short-Term Memory), which is effective for sequential data such as time series.

### Architecture
- **LSTM Layer**: Captures sequential patterns in the data.
- **Dense Layer(s)**: Output layer(s) for predicting PM2.5 concentrations.
- **Activation Function**: ReLU used in hidden layers.

## Evaluation

The model's performance is evaluated using RMSE (Root Mean Squared Error), and training results are provided in the notebook.

## Future Improvements

- Hyperparameter tuning for better performance.
- Experiment with different model architectures (e.g., stacked or bidirectional LSTM).
- Additional feature engineering to improve predictions.
