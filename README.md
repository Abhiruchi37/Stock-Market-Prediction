# Stock-Market-Prediction
## Overview

This project aims to predict stock market trends using machine learning techniques. By analyzing historical stock data, we build predictive models to forecast future stock prices. The project employs a Linear Regression to make predictions.

## Features

- Historical stock data analysis.
- Implementation of Linear Regression.
- Evaluation of model performance.
- Visualizations to interpret results.

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/Abhiruchi37/Stock-Market-Prediction.git
    cd Stock-Market-Prediction
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Download dataset (ex: 'INFY.csv')

4. Run the Notebook:

   ```bash
   jupyter notebook StockMarketPrediction.ipynb

   ```

## Dataset

The dataset('INFY.csv') includes the following columns:

- `Date`: Date of the stock data.
- `Symbol`: Stock symbol.
- `Series`: Security type (e.g., EQ for equity).
- `Prev Close`: Previous day's closing stock price.
- `Open`: Opening price of the stock.
- `High`: Highest price of the stock during the day.
- `Low`: Lowest price of the stock during the day.
- `Last`: Last traded stock price during the day.
- `Close`: Closing price of the stock on current day.
- `VWAP`:  Volume Weighted Average Price.
- `Volume`: Total shares traded.
- `Turnover`: Total value of stocks traded.
- `Trades`:  Total number of trades executed.
- `Deliverable Volume`: Volume of physically delivered shares.
- `%Deliverable`:  Percentage of deliverable volume out of the total volume traded.

## Model Performance

Evaluate the performance of the model using appropriate metrics such as  Mean Squared Error (MSE).


## License

This project is licensed under the [MIT License](LICENSE).
