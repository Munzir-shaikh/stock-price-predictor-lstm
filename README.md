# stock-price-predictor-lstm

# 📈 Stock Price Prediction with LSTM (AAPL)

This project predicts the **closing price of Apple Inc. (AAPL)** stock using historical stock data and an LSTM (Long Short-Term Memory) neural network. It uses data pulled directly from **Yahoo Finance** via `yfinance`, and is built using Python, TensorFlow, and Scikit-learn.

---

## 🚀 Features

- Fetches live historical data for AAPL from Yahoo Finance
- Preprocesses and scales stock data
- Uses look-back windows to create LSTM-compatible sequences
- Trains an LSTM model on past prices to predict future closing prices
- Plots actual vs predicted prices for evaluation
- Achieves high prediction accuracy:  
  - 🧮 **MAE:** ~4.59  
  - 📊 **R² Score:** ~0.93

---

## 📦 Tech Stack

- Python 3.10
- TensorFlow / Keras
- Scikit-learn
- yfinance
- Jupyter Notebook
- Matplotlib

---

## 🧠 Model Summary

- Model: Sequential LSTM
- Input: Past 20 days of closing prices
- Output: Next day's closing price
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

---

📌 Future Improvements
- Add more features (volume, moving averages, technical indicators)
- Apply to other stocks (e.g., TCS.NS, INFY.NS)
- Build a web app using Streamlit
- Implement walk-forward validation or multi-step prediction



📜 License
MIT License — use freely, give credit if helpful 😊


🙋‍♂️ Author
Munzir Shaikh
Data Science Engineering student | Java & Python learner



