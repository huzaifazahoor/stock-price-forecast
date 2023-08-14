# Price Prediction with Prophet

Forecast stock price trends using Python and the Prophet library.

![Stock Forecasting](https://miro.medium.com/v2/resize:fit:875/1*aoGkoJX5WAIMQ5b73Dk-vQ.png)

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)

## About

This repository is dedicated to forecasting stock price trends. By leveraging the power of the Prophet library, the code fetches historical stock data, preprocesses it for model compatibility, trains a forecasting model, and visualizes the predicted stock price trends. The code is modular and adaptable for various stocks and timeframes.

## Installation

1. Clone this repository:
   ```git clone https://github.com/huzaifazahoor/stock-price-forecast```

Navigate to the project directory:

```cd stock-price-forecast```

Install the required packages:

```pip install -r requirements.txt```

## Usage

Set up your Financial Modeling Prep API key as an environment variable named FMP_API_KEY.

Run the main script:

```python main.py```

The script will fetch data for Apple (AAPL) by default. Modify the symbol variable in the main() function to forecast for different stocks.