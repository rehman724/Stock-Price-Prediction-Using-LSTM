# Stock-Price-Prediction-Using-LSTM
## Project Overview
This project leverages historical American Airlines (AAL) stock price data to develop a predictive model using Long Short-Term Memory (LSTM) neural networks. The model is trained on a windowed dataset, where each sample consists of a sequence of past prices, and is evaluated on its ability to accurately forecast future prices on validation and testing sets. Recursive predictions are also made to demonstrate the model's performance in a real-world scenario.
# Technical Details
## Data Preprocessing
The project utilizes the pandas library to load and preprocess the AAL stock price data from a CSV file. The data is then transformed into a suitable format for modeling, including date conversion and feature selection.
## Model Architecture
The LSTM model is defined using the Keras API, with a sequential architecture comprising an input layer, an LSTM layer, and two dense layers. The model is compiled with mean squared error loss and Adam optimizer, and trained on the training data with validation data.
## Evaluation Metrics
The model's performance is evaluated using mean absolute error (MAE) and mean squared error (MSE) metrics. The results are visualized using matplotlib to facilitate comparison and analysis.
## Recursive Prediction
The project demonstrates the model's ability to make recursive predictions, where each prediction is used as input to make the next prediction. This approach simulates real-world scenarios where predictions are made iteratively.
# Getting Started
- git clone https://github.com/rehman724/American-Airlines-Stock-prediction-using-LSTM.git
- pip install -r requirements.txt
- python american_airlines_stock_price_prediction.py
