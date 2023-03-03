#Summary of comparison of various models that can be used for predicting the Amazon stock prices   

Here is the summary:

1) Basically there are various Ml models which we can use to predict the output these include Linear Regression , Moving Average,Auto-Regressive,
ARMA and ARIMA out of AR,MA,ARMA and ARIMA out of these ARIMA is the most Accurate one.

2) WE can apply Linear Regression only in case of when there is a linear relationship between the dependent and the independent variable. 

3) The primary difference between Linear Regression and ARIMA model 
   a)  In case of Linear Regression we have a dependent variable whose value is calculated by the help of some independent variables.
       It assumes there is a linear relationship between independent and dependent variable.
   b)  No concept of Linear relationship between input and output varible in case of ARIMA.ARIMA it has three parameters (p,d,q) where p is the order of autoregressive model, d is the degree of differencing, and q is the order of moving-average model. 
       ARIMA models use differencing to convert a non-stationary time series into a stationary one and it also make use of the past values to predict future values.

4) ARIMA model work only in case of stationary data if data is non-stationary then we need to convert it into stationary one.

5) In stock price prediction(when there is data present on daily basis) the ARIMA does not perform that much well. If we increase the no of future values to predict 
   then in that case the root mean square error will also increase.From this we conclude that ARIMA models are more suitable for monthly and yearly data.

6) Difference between ARIMA and MA 
   a) Moving Average is simply a naive approach It calculates the future output based on past values.Accuracy will be lower as this model is pretty basic.
   b) ARIMA model includes Moving Average model along with Auto-Regression and Integration so It has all the features of MA and also it has some additional features 
      thats why it performs better in comparison to MA model.

7) Same is the case with AR and ARMA models.ARIMA has all the features of AR and ARMA and also it has some additional features 
      thats why it performs better in comparison to AR and ARMA model.

8) Very few techniques became useful for forecasting the stock market as it changes with the passage of time. As time is playing a crucial rule here, 
Time Series (TS) analysis can be used to predict short-term stock market.





# How to run the Amazon.ipynb file?
You can run the Amazon.ipynb in jupiter notebook or you can run the file using google colab notebook.You just need to click on each cell to run the cell. make  sure you run the pip install commands present in the code before you running the other cells.  


# what the Amazon.ipynb do or return as ouput ?
Basically It will predict the ouptut (closing price of amazon stock) for the next 57 days.





 
