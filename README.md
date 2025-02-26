# Stock Price Prediction using LSTM

## Description
This project predicts the stock price of Apple Inc. (AAPL) using a Long Short-Term Memory (LSTM) neural network. The model is trained on historical stock data fetched using the Yahoo Finance API.

## Technologies Used
- Python
- Yahoo Finance (`yfinance`)
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow/Keras

## Features
- Fetches historical stock price data using Yahoo Finance
- Preprocesses and scales data for training
- Uses LSTM layers to train a model for predicting stock prices
- Visualizes real vs. predicted stock prices
- Saves the trained model for future use

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the script to fetch data, train the model, and visualize predictions:
```bash
python stock_price_prediction.py
```

## File Structure
- `stock_price_prediction.py` - Main script for fetching data, training the model, and plotting predictions.
- `stock_price_forecasting_model.h5` - Saved LSTM model after training.
- `requirements.txt` - List of required Python libraries.

## Results
The model predicts stock prices and plots real vs. predicted values for visualization.

## License
This project is licensed under the MIT License.

## Contribution
Feel free to fork, contribute, or suggest improvements!

## Author
[Ariya Birjandi](mailto:ariyabirjandi87@gmail.com)

