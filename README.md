# Stock-Market-Price-Prediction
Stock closing price prediction using LSTM neural networks
# Stock Market Price Prediction Using LSTM

## Project Overview
This project demonstrates stock closing price prediction using a Long Short-Term Memory (LSTM) neural network. It uses historical daily closing-price data to learn time-series patterns and estimate future closing prices.

## Objectives
- Load and clean the stock dataset.
- Normalize closing-price values.
- Generate sequences using a 60-day lookback window.
- Train an LSTM model.
- Evaluate predictions using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- Visualize actual versus predicted prices.
- Generate illustrative future forecasts.

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## Dataset
File: `Stock_Market_Dataset_Kaggle.csv`

The dataset contains Date, Open, High, Low, Close, Adjusted Close, Volume, and Ticker columns. Verify the dataset's source and whether its prices are synthetic before interpreting the results as real market predictions.

## How to Run
1. Open the notebook in Google Colab.
2. Upload the CSV dataset when prompted.
3. Run the notebook cells in order.
4. Review the MAE, RMSE, and prediction plots.

## Disclaimer
This is an educational machine-learning project. Forecasts are experimental estimates, not financial advice or guaranteed predictions of actual market prices.
