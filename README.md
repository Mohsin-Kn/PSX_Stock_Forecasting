
# PSX Stock Forecasting 

This project leverages a deep learning approach—specifically, a Long Short-Term Memory (LSTM) network—to predict the future stock price movements of **OGDC.KA**, the ticker symbol for Oil & Gas Development Company Limited listed on the Pakistan Stock Exchange (PSX). By analyzing historical data comprising daily Open, High, Low, and Close (OHLC) prices along with trading volume, the model captures complex temporal patterns and trends inherent in financial markets to deliver robust next-day price predictions.

---

## 📈 Data Source
- **Source**: Yahoo Finance via `yfinance`
- **Ticker**: OGDC.KA
- **Period**: Jan 2021 – Jun 2025 (1,150 days)
- **Features**: Open, High, Low, Close + Volume

---

## 🧠 Model
- **Algorithm**: Long Short-Term Memory (LSTM)
- **Input**: 30-day historical sequences
- **Output**: Next-day price prediction
- **Optimization**: Adam, MSE loss

---


## 🛠 Setup and Run

```bash
# Clone the repository
git clone https://github.com/Mohsin-Kn/PSX_Stock_Forecasting.git
cd PSX_Stock_Forecasting

# Create a virtual environment
python -m venv venv

# Activate the environment
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

