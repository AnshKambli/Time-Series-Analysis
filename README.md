#Stock Price Prediction with ARIMA
This project is a Python-based application that uses the ARIMA (AutoRegressive Integrated Moving Average) model to predict stock prices for a user-specified number of days into the future. The project fetches real-time stock data from Yahoo Finance (yfinance) and generates insightful visualizations, including confidence intervals and historical trends.
Features
Stock Data Fetching: Real-time stock data is downloaded using Yahoo Finance's API (yfinance).
ARIMA Modeling: The ARIMA model is implemented for time series forecasting, making accurate next-day (or custom-day) predictions.
Interactive Forecasting: Users can specify how many days into the future they want to forecast the stock price.
Visual Insights:
Historical stock prices and forecasted prices are displayed on a single graph.
Confidence intervals are shaded for better understanding of prediction uncertainty.
Highlights last known price for context.
Customizable: Easily adaptable for any stock ticker supported by Yahoo Finance.
How It Works
Input: The user specifies the stock ticker (e.g., TCS.NS) and the number of days to forecast.
Model Training: An ARIMA model is trained on historical closing prices.
Prediction: The model predicts the stock price for the specified future date.
Visualization: A graph is generated displaying:
Historical stock prices
Forecasted price and confidence intervals
Last known price for comparison
Output: The forecasted price and date are displayed below the graph
Prerequisites
Make sure you have the following installed on your system:
Python 3.7 or higher
Contributions
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request. For major changes, open an issue first to discuss what you'd like to change.
