# AR Model : AutoRegressive

-The AR model is simply an extension of the random walk that includes terms further back in time. 
**The structure of the model is linear, that is the model depends linearly on the previous terms, with coefficients for each term**. This is where the "regressive" comes from in "autoregressive". It is essentially a regression model where the previous terms are the predictors.

- the mean of a AR(p) process is 0
- AR(1) = random walk


# MA Model : MovingAverage

-It is a linear combination of the past white noise terms.


![image](https://github.com/Eliegautie/Forecasting-models/assets/105276166/2e50f8a4-083b-4166-b6d7-9a32b8d9422f)

#
#



# ARMA(p,q) Model:


![image](https://github.com/Eliegautie/Forecasting-models/assets/105276166/7fc4f65d-3ced-4ae8-bcd9-abdb73244a82)


ARMA(p,q) : p = AR order : number of past values
            q = MA order : number of past residuals
            
#
#


# ARIMA(p,d,q) Model:


![image](https://github.com/Eliegautie/Forecasting-models/assets/105276166/9012d249-25a3-4526-80c2-8f3bfcc7ddac)


#
#



**ARCH/GARCH model : useful when the goal of the study is to analyze and forecast volatility :  Variance Model.**


# ARCH Model : AutoRegressive Condtional Heteroskedasticity

- Autoregressive : depends on its own past
- Conditional : variance depends upon past information
- Heteroskedasticity : it is for non-constant variance.

heteroskedasticity is when the variance of the underlying distribution used to construct our time series changes as a function of time

#
#


# GARCH Model : Generalized AutoRegressive Condtional Heteroskedasticity:


- In a **Garch(p,q)** model for condtional variance, forecasts depend on a (non-negatively) weighted sum of **past squared residuals** (from some condtional mean function model) and **past variance forecasts**.

- The Garch model is divided into two parts: the symmetrical model (identical volatility response to positive or negative shocks) and the asymmetrical model (the effect of bad and good news is not the same, with bad news having a greater impact on volatility).



![image](https://github.com/Eliegautie/Forecasting-models/assets/105276166/c3cbd69a-71a6-4fe4-b2d5-5d179804b47f)


Garch (p , q) : p = Arch order : number of past squared residuals
                q = Garch order : number of past conditional variances







