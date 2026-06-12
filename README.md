NIFTY-50 Investment Intelligence Platform

Overview

This project is an AI-powered financial analytics and investment intelligence platform built using historical NIFTY-50 stock market data from 2000–2021.

The system performs:

* Exploratory Data Analysis (EDA)
* Technical Indicator Engineering
* Risk Assessment
* Portfolio Construction
* Machine Learning-Based BUY Signal Prediction
* Backtesting against Buy-and-Hold Strategy

The project combines quantitative finance concepts with machine learning to generate explainable investment recommendations.

⸻

Dataset

Dataset used:

* NIFTY50_all.csv
* stock_metadata.csv

Source:

* Kaggle NIFTY-50 Historical Dataset

Period Covered:

* January 2000 – April 2021

⸻

Features Engineered

The project creates 20+ technical and statistical indicators including:

* RSI
* MACD
* Bollinger Band Width
* Rolling Volatility
* Momentum
* VWAP Difference
* Volume Ratio
* Delivery Strength
* Price vs MA50
* Daily Returns

⸻

Machine Learning Model

Primary Model:

* Random Forest Classifier

Problem Type:

* Binary Classification

Target:

* Predict whether stock price will rise more than 3% in the next 20 trading days.

⸻

Performance Metrics

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Approximate Results:

* Accuracy: ~68%
* ROC-AUC: ~0.74

⸻

Portfolio Types

The system generates three investment portfolios:

1. Conservative Portfolio
2. Balanced Portfolio
3. Aggressive Portfolio

Each portfolio is constructed using quantitative risk-return metrics.

⸻

Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* ReportLab
* Jupyter Notebook

⸻

Project Structure

project/
│
├── data/
├── notebook/
├── app.py
├── requirements.txt
├── README.md
├── model.pkl
├── scaler.pkl
└── NIFTY50_Technical_Report.pdf

⸻

Future Improvements

* LSTM/Deep Learning integration
* Live NSE API integration
* Real-time prediction dashboard
* Portfolio optimization using Markowitz theory
* Dynamic risk-free rate adjustment

⸻

Author

Amar Kumar 
23113021
Aditya Raj
23113021

Civil Engineering Department
IIT Roorkee