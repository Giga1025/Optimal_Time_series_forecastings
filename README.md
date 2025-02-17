# Time series forecasting

## introduction
Time series forecasting is a method of using machine learning models to predict the future outcomes, sounds similar to our normal regression, but the main thing to remember is that the data here follows a trend and seasonality, meaning the future data depends on the current and previous data. This concept is called temporal dependency.

Our classic machine learning models cannot accurately predict the values for temporal data,because they are not designed to predict the future values using the previous data, hence we use forcasting models such as AR, ARIMA, SARIMA and XGBOOST(Not really forecasting model, but we modify it to act like a forecasting model)

## Aim 
The aim of the project is to show that, with enough feaeture engineering any machine learning model will be able to predict temporal data and we plan to do it by performing feature engineering on XGBOOST.

## Further information.
Please look into this blog ive written to get a thorough understanding of the project. 
[Time series Forecasting using Xgboost](https://medium.com/@byashwanth77/forecasting-using-xgboost-lag-and-decomposition-864815bd98c5)
