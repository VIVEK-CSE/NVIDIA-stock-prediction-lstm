# NVIDIA Stock Price Prediction using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict future NVIDIA (NVDA) stock prices based on historical data.

## Objective

Build and train an LSTM model to forecast the next day's adjusted closing price for NVIDIA stock.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy & Pandas
- Matplotlib
- Scikit-learn

## Dataset

- Dataset used: `NVDA.csv` (Historical stock data)
- Source: Kaggle

## Model Architecture

- 2 LSTM layers (50 units each)
- Dropout layers to prevent overfitting
- Dense output layer (1 neuron)
- Mean Squared Error (MSE) loss
- Adam optimizer
- Early stopping based on validation loss

## Evaluation Metric

- **RMSE (Root Mean Squared Error)** is used to evaluate performance.

## How to Run

1. Download NVIDIA stock dataset (`NVDA.csv`)
2. Place it in the path
3. Run `lstm_nvda_predictor.py` (the main script)
4. View prediction graphs and next-day price in terminal

## Output

- Line graph comparing actual vs predicted prices
- Printout of the predicted price for the next day

## Sample Output

-Root Mean Squared Error (RMSE): 3.14
-Predicted NVIDIA stock price for the next day: $130.40
