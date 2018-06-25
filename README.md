#Timeseries_forecasting

Timeseries forecasting is one important area of the Machine Learning.

It deals with respect to the time at regualar intervals(days,Months,Years).There are many ML models which deals with the Timeseries Forecasting.

Assumptions:The time has to be divided at equal intervals and the data has to be stationary and continuous without any random values which we call it as outliers 

The models which deal mainly are :

ARIMA is the universal models where most datascientists will be using for the Timeseries Forecasting.we have the model Auto-ARIMA in R where it can select automatically the ARIMA order which will be suited for the dataset.But in Python we don't have this option where we have to go throuth with all the orders and select the required ARIMA order best suited for the respected dataset.This is the main aim of this project.

SARIMAX is the extension of the ARIMA where it mostly deals with the seasonality data.I have automated the ARIMA order with respected to the dataset along with the seasonality applied to it.
