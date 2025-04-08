# Bitcoin-Price-Prediction-using-Machine-Learning
The Bitcoin Price Prediction using Machine Learning project aims to forecast future values of Bitcoin (BTC-USD) based on its historical price trends. By applying machine learning algorithms to time-series financial data, the project seeks to uncover patterns .
# 🪙 Bitcoin Price Prediction using Machine Learning

This repository contains a project on **Bitcoin (BTC) Price Prediction** using **Machine Learning** techniques. The objective is to forecast the future price of Bitcoin based on historical market data using regression-based models.

---

## 📌 Project Highlights

- 📉 Time-series prediction of Bitcoin closing prices.
- 🧠 Implementation of multiple machine learning models.
- 📊 Comparative analysis of regression performance.
- 📁 Input data: Historical Bitcoin prices in `.xls` format.
- 🛠️ Jupyter Notebook-based implementation for ease of analysis.

---

## 🚀 Features

- ✅ Historical data analysis for Bitcoin (BTC-USD).
- ✅ Preprocessing and feature engineering on financial time-series data.
- ✅ Training of models like Linear Regression, Random Forest, and more.
- ✅ Visualization of actual vs. predicted prices.
- ✅ Evaluation using MAE, MSE, RMSE, and R² score.
- ✅ Extendable to incorporate LSTM or deep learning models.

---

## 💻 Installation

Ensure you have **Python 3.8+** and install the required dependencies using:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn openpyxl
Project Structure
php
Copy
Edit
├── data/
│   ├── BTC-USD.xls           # Historical Bitcoin price data
│   └── class.xls             # Labels or additional classification info
├── notebook/
│   └── Untitled.ipynb        # Jupyter Notebook with full ML pipeline
├── models/                   # (Optional) Trained model files (.pkl or .h5)
├── plots/                    # (Optional) Prediction plots and evaluation graphs
├── README.md                 # Project documentation
▶️ Running the Project
Open the Jupyter Notebook:


Follow the steps to:

Load and preprocess data from BTC-USD.xls and class.xls.

Perform exploratory data analysis (EDA).

Train regression models.

Predict and visualize Bitcoin prices.

Evaluate the performance of each model.

📊 Data (BTC-USD.xls)
The dataset includes:

Date

Open, High, Low, Close Prices

Volume

Class label info (from class.xls if applicable)

Output Example
Actual vs. Predicted price graph

Model accuracy metrics such as MAE, RMSE, and R²

Models Used:
Linear Regression

Decision Tree Regressor

Random Forest Regressor

Support Vector Regression (SVR)

Future Enhancements
Integrate deep learning models (LSTM, GRU).

Add real-time Bitcoin data streaming using APIs.

Build a web dashboard using Streamlit or Flask.

Incorporate sentiment analysis from news or Twitter.

📌 License
This project is licensed under the MIT License. Feel free to use and modify it with attribution.

Author: Rithik
Email: kumarrithik700@gmail.com

