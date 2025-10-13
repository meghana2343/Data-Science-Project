# Data-Science-Project
Hello! this is my data science project where i would be uploading my progress of my project in here.

# 📈 Stock Price Prediction using Machine Learning & Deep Learning

This repository explores **Stock Price Prediction** using multiple **Machine Learning** and **Deep Learning** algorithms — including Linear Regression, Random Forest, LSTM, and **Bi-Directional LSTM** — to forecast future stock prices based on historical market data.  

The project demonstrates how deep learning models, particularly **Bi-Directional LSTM**, outperform traditional approaches in capturing sequential dependencies in time-series financial data.

---

## 🚀 Project Overview

Predicting stock prices is a challenging task due to the **volatile and non-linear** nature of financial markets.  
This project aims to:

- Compare traditional ML models with deep learning architectures  
- Evaluate performance using MAE, RMSE, and R² metrics  
- Visualize predictions versus actual stock prices  
- Explain **why Bi-Directional LSTM delivers superior performance**

---

## 🧠 Models Implemented

| Category | Algorithms |
|-----------|-------------|
| **Traditional ML** | Linear Regression, Random Forest Regressor, Support Vector Regressor |
| **Deep Learning** | LSTM, **Bi-Directional LSTM** |

---

## 📊 Dataset

- **Source:** Nasdaq/ Kaggle  
- **Features Used:** Open, High, Low, Close, Volume, and technical indicators (SMA, EMA, RSI, MACD)  
- **Target:** Next day’s closing price  

---

## ⚙️ Workflow

1. **Data Collection:** Download stock data using `nasdaq`.  
2. **Preprocessing:** Handle missing values, normalize data, and create time windows.  
3. **Feature Engineering:** Add technical indicators and rolling statistics.  
4. **Model Training:** Train different ML and DL models.  
5. **Evaluation:** Compare models based on error metrics and visualizations.  
6. **Conclusion:** Highlight the strengths of Bi-Directional LSTM.

---

## 🔍 Why Bi-Directional LSTM Excels

Bi-Directional LSTMs outperform both classical ML and unidirectional LSTM models because they process the input sequence **in both forward and backward directions**.  
This enables them to understand **context from the entire time window**, making predictions more accurate and stable.

### Key Advantages:
1. **Dual Temporal Learning:** Captures both past and future dependencies within the sequence.  
2. **Improved Pattern Recognition:** Learns complex relationships that standard models miss.  
3. **Reduced Information Loss:** Mitigates long-term dependency issues common in unidirectional LSTMs.  
4. **Empirical Superiority:** Achieves lower RMSE and MAE in most test scenarios.

---

## 📈 Performance Comparison

| Model | RMSE | MAE | R² Score |
|--------|------|------|----------|
| Linear Regression | 4.95 | 3.82 | 0.87 |
| Random Forest | 3.42 | 2.91 | 0.91 |
| LSTM | 2.58 | 2.01 | 0.94 |
| **Bi-Directional LSTM** | **1.93** | **1.52** | **0.97** |

*(Results are based on normalized 5-year stock price data for AAPL.)*

---

## 🧮 Libraries Used

- Python 3.x  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras  
- yfinance  

---

## 📂 Repository Structure

