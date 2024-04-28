# Stock Price Prediction

This project aims to predict stock prices using machine learning models such as Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The models are trained on historical stock price data to forecast future prices.

## Installation
Follow these steps to get your development environment set up:

1. Clone the repository to your local machine.
2. Navigate to the project directory.

Technologies
The application is built with the following technologies:

- Python x3 or above
- Pandas
- Numpy
- matplotlib
- sklearn
- tensorflow

## Usage
1. Preprocess the data:
   - Clean the dataset.
   - Normalize the features.
   - Split the data into training and testing sets.

2. Train the models:
   - Train the CNN model.
   - Train the LSTM model.

3. Evaluate the models:
   - Compare the performance of the CNN and LSTM models.
   - Plot the actual vs. predicted closing prices.

## Directory Structure
stock-price-prediction/
│
├── data/
│ └── AAPL_use.csv
│
├── notebooks/
│ ├── CNN_Model.ipynb
│ ├── LSTM_Model.ipynb
|
├── requirements/
│ ├── base.txt
|
|├── paper/
│ ├── CAAI_Trans_on_Intel_Tech-2021-Mukherjee-Stock_market_prediction_using_deep_learning_algorithms.pdf
|
├── README.md
├── requirements.txt
└── LICENSE

## License Information
This project is licensed under the MIT License. For more details, see the [LICENSE file](./LICENSE).