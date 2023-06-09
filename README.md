# Google Stock Price Prediction Model

This repository contains a Jupyter Notebook with a deep learning model for predicting the stock prices of Google using LSTM (Long Short-Term Memory) and Bidirectional LSTM algorithms. The model is trained on historical stock price data in CSV format and can be used to make predictions for future stock prices.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before running this notebook, make sure you have the following prerequisites:

- Python (version 3.6 or later)
- Jupyter Notebook
- TensorFlow (version 2.0 or later)
- Numpy
- Pandas
- Matplotlib

## Installation

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/Google-Stock-Price-Prediction.git
   ```

2. Navigate to the cloned repository:

   ```bash
   cd google-stock-price-prediction
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the `Google_Stock_Price_Prediction.ipynb` notebook.

## Usage

The Jupyter Notebook contains all the necessary code and explanations to train, evaluate, and make predictions using the LSTM and Bidirectional LSTM models.

## Model Architecture

The LSTM (Long Short-Term Memory) and Bidirectional LSTM (BiLSTM) are popular recurrent neural network (RNN) architectures. These models are well-suited for sequential data such as time series, where the order of the data points is important. LSTM and BiLSTM models have proven to be effective in capturing temporal dependencies and making accurate predictions.

The architecture of the LSTM model consists of LSTM layers followed by fully connected layers. The Bidirectional LSTM model extends the LSTM architecture by processing the input sequence in both forward and backward directions, resulting in a richer representation of the input sequence.

## Dataset

The dataset used for training and evaluation should be in CSV format. You can provide your own historical stock price data by placing the CSV file in the same directory as the Jupyter Notebook. The dataset should contain at least two columns: 'Date' and 'Close', representing the date and closing price of the Google stock, respectively.

You need to modify the notebook code to load your specific dataset file and preprocess it accordingly.

## Contributing

Contributions to this repository are welcome. If you have any improvements or bug fixes, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
