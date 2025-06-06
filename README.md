# Bitcoin Price Prediction using XGBoost

This project implements a machine learning model to predict Bitcoin price movements using XGBoost regression. The model uses various technical indicators and features to make predictions across different time horizons.

## Features

- Multiple prediction horizons (1-day, 7-day, 30-day, 180-day)
- Technical indicators including:
  - Moving averages (7-day, 30-day)
  - Volatility measures
  - Volume analysis
  - Price ratios
  - Lagged returns
- Rolling window training approach
- Comprehensive performance metrics

## Requirements

- Python 3.x
- pandas
- numpy
- xgboost
- scikit-learn

## Installation

```bash
pip install pandas numpy xgboost scikit-learn
```

## Usage

1. Ensure you have the required data file (`btc_1d_data_2018_to_2025.csv`)
2. Run the Jupyter notebook `main2.ipynb`
3. The notebook contains:
   - Data preprocessing
   - Feature engineering
   - Model training
   - Performance evaluation

## Model Performance

The model evaluates performance using:
- Total Return
- Annualized Return
- Sharpe Ratio
- Maximum Drawdown
- Win Rate
- Profit Factor
- Annual Returns by Year

## Notes

- The model uses a rolling window approach to simulate real-world trading conditions
- Trading decisions include a fee rate of 0.1%
- Predictions are capped to prevent unrealistic returns
- The model implements various risk management features

## License

This project is open source and available under the MIT License. 