# Multivariate Time Series Forecasting and Feature Importance

In this repository, we introduce the steps to prepare a time series dataset, train a deep learning model for prediction, and shed some light on how the model generates its forecasts by calculating feature importance. 

More specifically, we would forecast BTC-USD price using the LSTM model from `Pytorch`, and find the feature importance using the `SHAP` library.

The notebook included is an interactive one. Therefore, we recommend running it on your own machine for the best experience.

## Installation:

```
git clone https://github.com/duc-phamh/time_series_forecasting.git
conda create -n py39 python=3.9 -y
conda activate py39
cd time_series_forecasting
pip install -r requirements.txt
```

## License

This project is licensed under the Apache-2.0 License.
