# Transfer-Function-Modeing-Time-Series-Analysis

Problem Description:

A small city XYZ has been taking record of its monthly electricity consumption (in kilowatt hours) for about 10 years from 1997. Meanwhile, the monthly maximum temperature (in degree C) has also been recorded. The time series plots shown below indicate the varying of electricity consumption as well as temperature from Jan. 1997 to Dec. 2006. The data are included in the csv file (train.csv). A small part of them is shown as below.

![Time series Image](Transfer Function.jpg)

Requirements

The time series data was analyzed using the following tasks:

1)	Use the Holt-Winter forecasting method to build a temperature forecasting model. Choose the best exponential smoothing parameter.
2)	Develop a seasonal ARIMA model for temperature. Please clearly describe each step of your model building process. Compare this model with the model you found for Question 1), in terms of some performance statistics including MSE, MAD, and MAPE.
3)	Perform a spectral analysis of the temperature process to identify the significant frequency and make explanation.
4)	Develop a transfer function model to illustrate the change of electricity consumption with its relation to the exogenous variable – temperature. You may choose any temperature model developed for Question 1), 2) or 3). Please clearly describe each step of your model building process. Remember to show your model adequacy checks.
5)	Forecast the future streamflow of both monthly maximum temperature and electricity consumption for the next 6 months after Jun. 2006. 

This case study was evaluated based on

1)	The efforts that are shown on developing the models
2)	The model’s performance statistics, the quality of forecast. Note that the relative RMSE (Root Mean Square Error, RMSE = √MSE) of the testing data will be evaluated based on the true values of both monthly maximum temperature and electricity consumption.
