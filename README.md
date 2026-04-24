# Multi-Factor-Stock-Forecasting-FW

# Multi-Factor Machine Learning Framework for Stock Price Prediction

This repository contains the implementation of the multi-factor prediction framework introduced in our research: *"A Multi-Factor Machine Learning Framework for Stock Price Prediction Incorporating Market Styles and External Influences."*

## 📖 Overview
Predicting stock market closing prices is complex due to volatility and external factors. This project implements a unified framework that:
1.  **Identifies Market Styles** using clustering algorithms (Spectral, K-Means, etc.).
2.  **Analyzes News Sentiment** using the FinBERT model to gauge market perception.
3.  **Incorporates Macroeconomic Indicators** (Gold/Oil prices) to capture wider economic trends.
4.  **Forecasts Stock Prices** using a machine learning pipeline that leverages shared patterns across companies with similar market styles.

## 🚀 Key Features
- **Data Preprocessing:** Outlier smoothing and normalization.
- **Clustering:** Comparative analysis of Spectral, K-Means, DBSCAN, and Agglomerative clustering.
- **Sentiment Analysis:** FinBERT integration for financial context understanding.
- **Predictive Modeling:** Comparison of LSTM, BiLSTM, ANN, Ridge Regression, RF, and XGBoost.

## 🛠 Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Required Libraries:
  ```bash
  pip install pandas numpy scikit-learn transformers torch xgboost
