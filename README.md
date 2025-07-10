# 📈 Stock Price Prediction

A Streamlit app to predict stock prices and give buy/hold/sell recommendations using ML models.

## 🚀 Features

* Fetch stock data via Yahoo Finance
* Predict next-day price using:

  * Random Forest
  * Linear Regression
  * LSTM (optional)
* Show RMSE & R² scores
* Plot actual vs predicted prices
* Recommendation system (Buy/Hold/Sell)

## 🛠️ Tech Stack

* Python, Streamlit, yfinance, scikit-learn, TensorFlow (LSTM), Matplotlib

## ▶️ Run It

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 📝 Usage

Enter stock ticker, date range, and select models. View predictions, performance metrics, and get a trading recommendation.
