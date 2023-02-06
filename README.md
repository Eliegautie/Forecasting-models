# Model for forecasting CAC40 using ARIMA  
to applied the ARIMA models (autoregressive integrated moving average) in order to predict future values, we data need need to show evidence of non-stationarity in the sense of mean (but not variance/autocovariance), where an initial differencing step (corresponding to the "integrated" part of the model) can be applied one or more times to eliminate the non-stationarity of the mean function (the trend). I choose to analyze the CAC40 because it's the most relevant benchmark French stock market index.  

#Resample the datas:  
First step is to resample the data we got

