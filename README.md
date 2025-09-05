# Stock Price Forecasting with LSTM

A machine learning project that predicts stock prices for Intel (INTC), Domino's Pizza (DPZ), and Disney (DIS) using LSTM neural networks. The analysis uses 5 years of historical data from Yahoo Finance (2020-2025) to train deep learning models for price forecasting. The project includes comprehensive data analysis, model evaluation, and interactive visualizations to support investment decisions.

## Features
- Downloads and analyzes 5 years of stock data from Yahoo Finance
- Builds deep learning models using LSTM neural networks for price prediction
- Creates interactive charts and graphs to visualize stock trends and patterns
- Calculates technical indicators like 10, 20, and 50-day moving averages
- Evaluates model accuracy using standard metrics like Mean Absolute Error and R-squared

## Key Results
- **INTC**: Avg $38.64, downward trend, high volatility
- **DPZ**: Avg $396.06, strong upward trend  
- **DIS**: Avg $120.08, volatile with downward trend

## Data
- 1,256 daily records per stock (5 years)
- Features: Open, High, Low, Close, Volume
- Output: CSV files and interactive charts

## Limitations
- Historical data only - market unpredictability affects accuracy
- External factors (news, events) not included in model
