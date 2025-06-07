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
```

## 🚀 Usage

- Run the main script (e.g., `stock_predictor.ipynb`).
- When prompted, input the stock ticker symbol you want to analyze (e.g., `AAPL` for Apple).
- The app will:
  - Fetch historical stock data using the Yahoo Finance API.
  - Preprocess the data (scaling and sequence generation).
  - Train the LSTM model (or load a pre-trained model if available).
  - Predict future stock prices.
  - Display visualizations comparing actual vs predicted stock prices.

## ⚠️ Limitations & Known Issues

- Model accuracy depends on the quality and quantity of historical data.
- Predictions do not factor in external market events or news.
- Training can be time-consuming without GPU acceleration.
- Currently supports only single-stock ticker input.
- No real-time data streaming or prediction.

## 🌟 Future Enhancements

- Support for multi-feature inputs such as trading volume and technical indicators (e.g., MACD, RSI).
- Real-time prediction with live data feeds.
- Hyperparameter tuning to improve model performance.
- Incorporate external data sources (news sentiment, macroeconomic indicators).

## 👤 Author

Developed by Ifeanyi Ojji  
Connect on [LinkedIn](https://www.linkedin.com/in/ifeanyi-ojji/) | [GitHub](github.com/ifeanyiojji)

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) for deep learning frameworks  
- [Yahoo Finance](https://pypi.org/project/yfinance/) API for stock data retrieval  
- [Matplotlib](https://matplotlib.org/) for data visualization  
- [Scikit-learn](https://scikit-learn.org/) for preprocessing and evaluation

