# Stock-Market-Prediction-Model
# 📈 S&P 500 Stock Price Prediction using LSTM

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![yfinance](https://img.shields.io/badge/yfinance-Latest-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices of the S&P 500 index. It uses historical data to train the model and provides predictions for future stock prices.

## 🚀 Features

- Downloads historical S&P 500 data using yfinance
- Preprocesses and normalizes data for machine learning
- Implements an LSTM model using TensorFlow/Keras
- Visualizes actual vs predicted stock prices
- Provides next-day price prediction

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- pip package manager

## 🛠️ Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/sp500-stock-prediction.git
   cd sp500-stock-prediction
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## 💻 Usage

1. Run the main script:
   ```
   python stock_prediction.py
   ```

2. The script will:
   - Download S&P 500 data from 2010 to 2023
   - Train the LSTM model
   - Generate predictions for 2023
   - Display a graph of actual vs predicted prices
   - Print the next day's predicted price

## 📊 Sample Output

```
Prediction for next day: 4567.89
```

![Sample Prediction Graph](/path/to/sample_graph.png)

## 🧠 How it Works

1. **Data Collection**: Uses yfinance to download S&P 500 historical data.
2. **Preprocessing**: Normalizes the data using MinMaxScaler.
3. **Model Architecture**: 
   - LSTM layer with 50 units
   - Dense layer with 25 units
   - Output Dense layer with 1 unit
4. **Training**: The model is trained on data from 2010 to 2022.
5. **Prediction**: Generates predictions for 2023 and the next trading day.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/yourusername/sp500-stock-prediction/issues).

## 📝 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

## 🙏 Acknowledgements

- [yfinance](https://github.com/ranaroussi/yfinance) for providing an easy-to-use interface to Yahoo Finance data.
- [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) for the powerful machine learning framework.
- [scikit-learn](https://scikit-learn.org/) for data preprocessing utilities.

---
⌨️ with ❤️ by [Govind Rachapudi](https://github.com/GovindRachapudi7)
