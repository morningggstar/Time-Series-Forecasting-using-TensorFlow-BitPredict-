# Time-Series-Forecasting-using-TensorFlow-BitPredict-

## Project Overview
Cryptocurrency markets are known for their volatility, making price forecasting a challenging and important task. This project, BitPredict, applies time-series forecasting techniques using deep learning models in TensorFlow/Keras to predict daily Bitcoin (BTC/USD) prices.

The project covers the entire machine learning pipeline: data preprocessing, feature engineering, model development, evaluation, and forecasting. Multiple models (Dense, Conv1D, LSTM, N-BEATS) and ensemble methods were compared to identify the best-performing approach.

This work demonstrates practical knowledge in applied deep learning for finance, rigorous evaluation of models, and experiment tracking for reproducibility.


## Tech Stack
* Programming Language: Python
* Frameworks & Libraries:
  - TensorFlow/Keras (Deep Learning Models)
  - Pandas & NumPy (Data Handling)
  - Matplotlib (Visualization)
  - Scikit-learn (Preprocessing, Evaluation)
* Environment: Jupyter Notebook


## Key Features
✅ End-to-end forecasting pipeline built in TensorFlow for daily BTC/USD price prediction.
✅ Implemented and compared Dense, Conv1D, LSTM, and N-BEATS models.
✅ Designed ensemble models to combine predictions and improve robustness.
✅ Integrated feature engineering (e.g., Bitcoin block-reward halving) to enhance predictive accuracy.
✅ Performed multi-horizon forecasting (predicting multiple days ahead).
✅ Added uncertainty estimation using ensemble methods.
✅ Rigorous evaluation using MAE, MAPE, RMSE, MASE metrics.


## Results
* Deep learning models significantly outperformed the naïve baseline predictor.
* N-BEATS and ensemble models delivered the most accurate forecasts.
* Demonstrated how adding domain-specific features (like block halving events) improves model performance.
* Produced reliable multi-horizon forecasts that can be extended for practical use in financial applications.


