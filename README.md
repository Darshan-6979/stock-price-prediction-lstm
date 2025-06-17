# stock-price-prediction-lstm
📈 A deep learning model using LSTM to predict stock closing prices based on historical time series data. Trained on Apple (AAPL) stock from Yahoo Finance with 60-day lookback windows.


This project uses a Long Short-Term Memory (LSTM) neural network to predict the next day's stock closing price based on the past 60 days of historical data. The model is trained on Apple Inc. (AAPL) stock data retrieved from Yahoo Finance using the `yfinance` API.

---

## 🧠 Model Overview

- Input: Last 60 closing prices
- Output: Next day’s predicted price
- Model: 2 stacked LSTM layers + Dropout + Dense
- Framework: TensorFlow/Keras

---

## 📊 Performance

- Final training loss: ~0.0030
- Data: AAPL stock (2018–2023)
- Prediction output: Realistic next-day price forecast

---

## 🛠️ Technologies Used

- Python
- TensorFlow/Keras
- yfinance
- NumPy, pandas, matplotlib

---


