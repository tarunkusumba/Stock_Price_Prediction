# 📈 Stock Price Trend Prediction using LSTM (Deep Learning)

This project predicts future stock prices using past trends with a Long Short-Term Memory (LSTM) model — a powerful type of Recurrent Neural Network (RNN).  
It fetches real-time historical stock data from Yahoo Finance, trains a model, and optionally deploys a dashboard using Streamlit.

---

## 🎯 Objective

> Predict stock prices using historical data patterns and visualize future trends with LSTM.

---

## 🛠️ Tools & Libraries

- Python 🐍
- yfinance 📥
- Keras + TensorFlow 🤖
- Pandas, NumPy 🧮
- Matplotlib 📊
- TA (Technical Analysis library) 📈
- Streamlit (for optional deployment) 🌐

---

## 🧪 Dataset

- Live historical stock data fetched from [Yahoo Finance](https://finance.yahoo.com) using `yfinance` Python library.
- Examples:
  - ✅ `RELIANCE.NS` (Reliance Industries)

---

## 📚 Project Workflow

### 🔹 Step-by-step Mini-Guide:

1. **Fetch stock data** using `yfinance` API
2. **Normalize and sequence** the data
3. **Build LSTM model** using Keras
4. **Train the model** with stock sequences
5. **Evaluate** with metrics like MAE, MAPE
6. **Predict future stock prices**
7. **Plot actual vs predicted**


---

## 🧠 LSTM Architecture (Enhanced)

- 3 LSTM layers with 100 units
- Dropout layers for regularization
- Dense layers for output


---

## 📊 Sample Output

- Model Loss: `0.0035`
- Plot of Actual vs Predicted & Future Forecast (7 days)

---

## 📦 Deliverables

- ✅ `Jupyter Notebook` (`stock_predictor_lstm.ipynb`)
- ✅ Trained Model Weights (`model.h5`)
- ✅ Visualizations (`predictions.png`)
- ✅ `Streamlit App` (Optional: `app.py`)
- ✅ README documentation

---

## ▶️ To Run

```bash
pip install -r requirements.txt
jupyter notebook
