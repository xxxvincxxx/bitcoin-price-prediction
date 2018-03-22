## Bitcoin price prediction strategies

In this repo some notes and test I gathered lately with regard to methodologies for forecasting time series, where non-linear trends are fit with yearly and weekly seasonality, with robustness wrt missing data, shifts in the trend, and large outliers. 

* [LSTM Model](https://www.researchgate.net/publication/13853244_Long_Short-term_Memory)

This [notebook](https://github.com/xxxvincxxx/bitcoin-price-prediction/blob/master/bitcoin_prediction_LSMT.ipynb) aims to provide an example of how a Recurrent Neural Network (RNN) using the Long Short Term Memory (LSTM) architecture can be implemented using TensorFlow. In this tutorial, this model is used to predict bitcoing prices.

* [Backtest Strategy via Catalyst](https://github.com/enigmampc/catalyst)

This [notebook](https://github.com/xxxvincxxx/bitcoin-price-prediction/blob/master/backtest_strategy.ipynb) uses Catalyst, an algorithmic trading library for crypto-assets written in Python. It allows trading strategies to be easily expressed and backtested against historical data (with daily and minute resolution), providing analytics and insights regarding a particular strategy's performance