# 📈 Stock Price Anomaly Detection using Machine Learning

## 📌 Project Overview
A real-time ML system that detects unusual stock price movements in Indian markets 
using an Adaptive Isolation Forest algorithm. Sends instant Telegram alerts when 
anomalies are detected.

## 🛠️ Technologies Used
- Python
- yFinance (Live stock data)
- Scikit-learn — IsolationForest
- Matplotlib (Visualization)
- Telegram Bot API (Real-time alerts)
- Google Colab

## 📊 Stocks Monitored
TCS, Infosys, Reliance, HCL Tech, Wipro (NSE)

## 🔄 Project Workflow
1. Fetch live 1-minute interval stock data via yFinance
2. Compute rolling volatility
3. Apply Adaptive Isolation Forest to detect anomalies
4. Plot price, anomalies, and volatility charts
5. Send Telegram alert if latest data point is anomalous
6. Save results to CSV

## 💡 Key Features
- Adaptive contamination rate based on market volatility
- Supports multiple stocks in one run
- Auto-saves plots (PNG) and data (CSV)
- Real-time Telegram notifications

## 👤 Author
**Kilari Poorna Chandra Vihari**
[LinkedIn](https://www.linkedin.com/in/viharikilari) | [GitHub](https://github.com/viharikilari)
