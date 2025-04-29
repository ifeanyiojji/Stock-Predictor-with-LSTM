# Stock-Predictor-with-LSTM

# 📈 Stock Price Predictor with LSTM

A deep learning project using Long Short-Term Memory (LSTM) neural networks to predict stock price trends based on historical data. This project demonstrates the use of time-series modeling, feature engineering, and data visualization to generate actionable financial insights.

## 🔍 Overview

This project aims to:
- Predict future stock closing prices using LSTM.
- Visualize historical vs predicted trends.
- Offer a reproducible workflow for time-series forecasting using Python.

## 🚀 Key Features

- ✅ Built with **TensorFlow** and **Keras** for deep learning.
- ✅ Data sourced via **Yahoo Finance API**.
- ✅ Preprocessing includes scaling, sequence generation, and reshaping for LSTM input.
- ✅ Model achieves **85%+ trend prediction accuracy** on test data.
- ✅ Visualization of model predictions vs actual stock prices using **Matplotlib**.

## 📊 Technologies Used

- Python
- NumPy & Pandas
- TensorFlow/Keras
- Yahoo Finance API (`yfinance`)
- Matplotlib
- Scikit-learn

## 🧠 How It Works

1. **Data Collection**: Historical stock data is fetched using the `yfinance` API.
2. **Preprocessing**: Data is scaled and transformed into sequences suitable for LSTM input.
3. **Model Training**: A sequential LSTM model is trained on the processed data.
4. **Evaluation & Visualization**: Model predictions are compared to actual data to assess performance.

## 🛠️ Installation

```bash
git clone https://github.com/ifeanyiojji/Stock-Predictor-with-LSTM.git
cd Stock-Predictor-with-LSTM
pip install -r requirements.txt
