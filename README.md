# Stock Price Prediction with Linear Regression

This repository contains a simple Python script that uses the Alpha Vantage API to download stock market data and a Linear Regression model to predict the next day's closing price. It also generates a graph to visualize the comparison between actual and predicted prices.

## Features

* **Data Download:** Fetches historical stock data from the Alpha Vantage API.
* **Model Training:** Trains a Linear Regression model based on the previous day's closing price.
* **Prediction:** Predicts the closing price for the next trading day.
* **Visualization:** Plots a graph of actual versus predicted prices using Matplotlib.

## File Structure

The recommended file structure is as follows:

```
stock-prediction/
├── .gitignore
├── README.md
├── requirements.txt
└── stock_predictor.py
```

* **`.gitignore`**: This file contains rules to prevent sensitive information, such as your `API_KEY`, from being uploaded to GitHub.
* **`README.md`**: This file provides an overview of the project, setup instructions, and usage details.
* **`requirements.txt`**: This file lists all the Python libraries required for the project, such as `pandas`, `requests`, `scikit-learn`, and `matplotlib`.
* **`stock_predictor.py`**: This is the main Python script containing all the code for the stock price prediction.

## Setup and Installation

1.  **Clone the Repository:**
    ```bash
    git clone <repository-url>
    cd stock-prediction
    ```

2.  **API Key:**
    * Obtain a free API key from the [Alpha Vantage website](https://www.alphavantage.co/).
    * Store your API key as an environment variable instead of hardcoding it in the script.

3.  **Install Dependencies:**
    * Install the required libraries listed in the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the script:

```bash
python stock_predictor.py
```

When the script runs, the terminal will display the predicted price and a comparison of the test data. A graph will also be plotted to visualize the actual and predicted prices.

## Graphs

Here are some sample graphs and the corresponding terminal output.

### INFY Stock

This shows the terminal output for INFY stock data:
![INFY Stock Prediction Data](uploaded:image_f32fce.png-48dba91f-39ee-41a6-a5bd-f0b67b83b885)

This graph visualizes the actual vs. predicted prices for INFY:
![INFY Stock Price Prediction](uploaded:image_f32faf.png-94924a3c-3aeb-42a0-9b29-12656e745444)

### TCS Stock

This shows the terminal output for TCS stock data:
![TCS Stock Prediction Data](uploaded:image_f337ac.png-ca7953e9-c341-46bf-b3e5-a59726ab7ff9)

This graph visualizes the actual vs. predicted prices for TCS:
![TCS Stock Price Prediction](uploaded:Screenshot from 2025-08-01 12-30-55.png-5cdb70a4-1f5b-4db1-9ce6-ab9f014f810e)
