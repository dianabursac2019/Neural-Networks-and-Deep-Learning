# Neural-Networks-and-Deep-Learning

Deep Stacked Stateful and Stateless LSTM Recurrent Neural Network for Time Series Forecasting 

Class Project Code - CSC578
In this study we explore how the newly developed deep learning-based algorithms for forecasting time series data, such as "Long Short-Term Memory (LSTM)", performs on the time series data forecast.
This paper aims to compare different stateful and stateless LSTM models applied to weather time series data. Specifically, we study the effect of stateless and stateful techniques in choosing the different number of hidden layers in the models, namely the depth of the neural network and the number of units per each layer. We show how the different parameters have different impacts on the prediction performance by calculating RMSE and SMAPE for each model. In addition, the paired t-test was performed to compare the two set of RMSE observations coming from different models. Our experimental results show that the stateful model with 2 layers and 32 units demonstrates the best performance. 

Data set

In this work we explore a multivariate forecasting problem. The 14 different quantities (including air temperature, atmospheric pressure and humidity) were recorded every hour from 2009 to 2016 (both inclusive). Given a historical data of climate conditions, this study aims to predict the temperature of the next hour based on the climate conditions and temperature over the last 24 hours.  
The train data set contains 52566 data records and 15 columns where the first column is "Date Time" and the remaining 14 columns are climate measurements.
The test data set contain 17447 data records and 336 columns where 14 climate measurements over 24 hours are concatenated
