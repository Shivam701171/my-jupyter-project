# 📈 Stock Price Prediction using Auto ARIMA

This project focuses on predicting stock prices using the Auto ARIMA model – a time series forecasting method that combines Autoregressive (AR) and Moving Average (MA) components. The aim is to model historical stock data and generate reliable future price forecasts.

---

## 🧠 What I Did

- Collected and used stock price data from 1st April 2018 to 11th April 2025.
- Applied Auto ARIMA, which selects the best ARIMA(p, d, q) configuration automatically.
- Used differencing (d=5) to make the time series stationary.
- Modeled:
  - AR (Autoregressive): Uses past values and the φ parameter.
  - MA (Moving Average): Uses past errors and the θ parameter.
- Forecasted future prices based on the fitted model.

---

## 🔍 Key Concepts Used

- **Stationarity**: Ensured via differencing to stabilize mean and variance over time.
- **ARIMA**: Combines AR (Autoregression), I (Integration via differencing), and MA (Moving Average).
- **Auto ARIMA**: Automatically selects the best model parameters using AIC/BIC.

---

## 📊 Output (Sample Forecast)

(Insert a screenshot of your predicted vs actual prices plot here)  
You can use matplotlib or seaborn to generate a visual forecast chart.

---

## 🛠 Tech Stack

- Python  
- Pandas, NumPy  
- statsmodels (Auto ARIMA)  
- Matplotlib / Seaborn (for visualization)  
- Jupyter Notebook

---

## 🔮 What’s Next?

- Building models for short-term prediction:
  - 15-minute timeframe
  - 1-hour timeframe
- Extending this project to cryptocurrency (BTC, ETH, SOL, etc.)
- Exploring other forecasting techniques like:
  - SARIMA for seasonality
  - Prophet (Facebook’s open-source model)
  - LSTM (Deep Learning-based time series modeling)

---

## 📂 Files

- auto_arima_stock_prediction.ipynb – Main Jupyter notebook containing all code and explanation
![Forecast Chart](images/forecast_plot.png)
---

## 📬 Let’s Connect

If you're interested in time series forecasting, stock prediction, or machine learning, feel free to connect with me on LinkedIn: https://www.linkedin.com/in/your-profile

---

### ⭐ Give the repo a star if you find it helpful!
