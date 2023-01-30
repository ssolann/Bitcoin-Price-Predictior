# Bitcoin-Price-Predictior

This project predicts the future price of Bitcoin using historical data on the price of Bitcoin, along with data from Wikipedia about edits to the Bitcoin page. The prediction is made by training machine learning models on the combined data.

## Data
The data used for training the model consists of two parts:

Historical price data for Bitcoin
Wikipedia edits data for the Bitcoin page
The data is merged and pre-processed to prepare it for training the model.

## Model
The model used for making the predictions is a Random Forest Model. It predicts whether the price of Bitcoin will increase or decrease tomorrow. An XGBoost model is then used to further improve accuracy.

## Requirements
- JupyerLab
- Python 3.8+
- Python packages:
pandas,
yfinance,
scikit-learn,
xgboost,
mwclient,
transformers
