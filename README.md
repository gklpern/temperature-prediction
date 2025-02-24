# temperature-prediction
This project implements time series forecasting using LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural networks. The model predicts temperature data from the Jena Climate dataset.



📊 Dataset

The model uses the Jena Climate 2009-2016 dataset.

The dataset is downsampled by taking every 6th value.

Only the temperature column (T (degC)) is used for prediction.



🔍 Model Architecture

LSTM Model:

Two LSTM layers with 64 and 32 units

ReLU activation function

A Dense layer for output

GRU Model:

Two GRU layers with 64 and 32 units

ReLU activation function

A Dense layer for output

Both models use:

Adam optimizer

Mean Squared Error (MSE) as the loss function

Early stopping for better generalization

📈 Results

The models are evaluated using MSE and visualized with real vs. predicted values:

Loss graphs for both LSTM and GRU models

Forecast plots comparing real temperature data with predictions
