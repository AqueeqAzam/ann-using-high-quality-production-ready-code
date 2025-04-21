# ann-using-high-quality-production-ready-code

# Stock Price Prediction with Advanced Neural Network

This project implements a robust stock price prediction system using a feedforward ANN in TensorFlow, designed for production-grade use.

## Workflow
![Stock Price Prediction Workflow](docs/workflow.png)

## Features
- Modular architecture with `StockPricePredictor`, `FeatureEngineer`, and `Config` classes.
- Robust preprocessing with KNN imputation and `RobustScaler`.
- Advanced ANN with Swish activation, Huber loss, and callbacks.

## Usage
Run the script to train, evaluate, and predict:
```bash
python stock_predictor.py
