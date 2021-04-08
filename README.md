# Forecasting Accuracy Comparison of Various Machine Learning and Statistical Models on Stock Market Price Movements
> See summary poster [here](https://github.com/ruankie/stock-market-prediction/blob/main/poster.pdf)

## Project Overiew
Accurate financial time series forecasts can assist investors in gaining a competitive
edge over other participants in capital markets. Previous research yielded contradicting
results pertaining to the superiority of machine learning (ML) over statistical
models in time-series forecasting. 

No empirical conclusion existed on what the
most accurate model(s) were for forecasting stock market price movements over
different forecast horizons. Existing studies either lacked comparisons to benchmarks,
lacked multi-step-ahead forecasts, or did not use a large enough data set for
statistically significant conclusions. 

This study compared the forecasting accuracy
of 20 different models on 403 time series of stocks/indices. These included four
ML, seven statistical, and two benchmark models as well as seven different combinations
of these models. The model forecast errors were assessed for 18 time steps
into the future according to three different accuracy measures (sMAPE, MASE, and
OWA). 

No conclusion could be drawn on whether pure ML models always performed
better or worse than pure statistical models. The top performing models
included combinations of both pure ML and pure statistical models. The Naïve
benchmark model outperformed all other models in this study for nearly all accuracy
metrics and forecast horizons tested. This suggests that when forecasting
monthly stock market price movements, no model from this study was more accurate
than a simple random walk model.

## Models Tested
* Statistical Models
	* Naive (random walk)
	* Simple exponential smooting
	* Holt’s linear trend
	* Damped exponential smoothing
	* Autoregressive (AR)
	* Autoregressive moving average (ARMA)
	* Autoregressive integrated moving average (ARIMA)
	* Theta method

* Machine Learning Models
	* Long short term memory (LSTM) neural network
	* Multi-layer perceptron (MLP)
	* Support vector regressor (SVR)
	* XGBoost

* Various combinations of the above models

## Acknowledgement
This project was funded by the DSI-NICIS National e-Science
Postgraduate Teaching and Training Platform (NEPTTP).
This project would not have been possible 
without the help from my supervisors Prof. Terence van Zyl
and Dr. Farai Mlambo.