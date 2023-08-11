# Gold Price Prediction using Artificial Neural Network (ANN)

This project demonstrates the use of an Artificial Neural Network (ANN) to predict gold prices based on various features. The model is trained using historical data and aims to predict gold prices accurately.

## Project Overview

The project uses Python, TensorFlow, and Keras to build an ANN model that predicts gold prices. It involves the following steps:

1. **Data Collection**: The project starts by importing historical data about gold prices and related features such as stock market indices, oil prices, and currency exchange rates.

2. **Data Preprocessing**: The data is split into features (input variables) and the target variable (gold prices). It's then scaled using MinMaxScaler to ensure that all features are on a similar scale.

3. **Model Architecture**: An ANN model is created using Keras. It consists of input layers, hidden layers with ReLU activation functions, and an output layer with a linear activation function.

4. **Compilation**: The model is compiled using the mean squared error loss function and the Adam optimizer.

5. **Training**: The model is trained using the training data with early stopping and model checkpoint callbacks. This helps prevent overfitting and saves the best model during training.

6. **Evaluation**: The trained model's performance is evaluated using the R-squared (R2) score on a test dataset.
