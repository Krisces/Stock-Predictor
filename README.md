# Stock Market Predictor

## Overview

The Stock Market Predictor is a web application that utilizes machine learning to predict stock prices based on historical data. Built with Streamlit, TensorFlow, and various data visualization libraries, this app allows users to input a stock symbol and view historical stock data, moving averages, and predicted prices.

You can try the web app I have created in [https://stock-predictor-kb.streamlit.app/](https://stock-predictor-kb.streamlit.app/).

## Features

- **Stock Data Visualization**: Displays historical stock data fetched from Yahoo Finance.
- **Moving Averages**: Visualizes the 50-day, 100-day, and 200-day moving averages of stock prices.
- **Price Prediction**: Uses a trained machine learning model to predict future stock prices based on past trends.

## Technologies Used

- **Python**: Programming language for the application.
- **Streamlit**: Framework for building web applications easily.
- **TensorFlow**: Machine learning library for building and training the stock prediction model.
- **yfinance**: Library for downloading historical stock price data from Yahoo Finance.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Library for numerical operations.
- **Matplotlib**: Plotting library for visualizing data.
- **scikit-learn**: Library for machine learning utilities (e.g., MinMaxScaler).

## Installation

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/Krisces/Stock-Predictor.git
```

### 2. Navigate to project directory

```bash
cd Stock-Predictor
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the streamlit app locally

```bash
streamlit run app.py
```
