# Insider Trading ML

Analyze and predict stock performance based on insider trading data.

## Overview

This project utilizes insider trading data to predict stock performance. By analyzing the transactions of company insiders, we aim to gain insights into potential stock price movements and make informed investment decisions.

## Features

- **Data Collection**: Fetch insider trading data from the Finnhub API.
- **Data Preprocessing**: Clean and preprocess the data for machine learning.
- **Machine Learning**: Use a Random Forest Regressor to predict relative stock performance based on insider trading data.
- **Visualization**: Visualize actual vs. predicted values and model residuals.

## Setup

### Prerequisites

- Python 3.x
- Required Python libraries: `requests`, `json`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`, `sklearn`

### Installation

1. Clone the repository:
```
git clone https://github.com/p-danilin/insider-trading-ML.git
cd insider-trading-ML
```
2. Install the required Python libraries:
```
pip install -r requirements.txt
```

### Configuration

Store your Finnhub API key in an environment variable or a `.env` file. If using a `.env` file, add the following line:
```
FINNHUB_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual API key.

## Usage

1. Run the `processing.ipynb` notebook to fetch, preprocess, and save the data.
2. Run the `training.ipynb` notebook to train the Random Forest model and visualize the results.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
