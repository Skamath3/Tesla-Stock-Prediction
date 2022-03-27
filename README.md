# Tesla-Stock-Prediction
**Predictive Analysis of Stock based on Historical Data in Python
The models used are LSTM Model and ARIMA.**

Dataset is taken from Yahoo Finance website for carrying out analysis 

At first, the program will split the data as 70%-train and 30%-test. I have trained the LSTM model by adding dense=1(1 layer) and lookback is 60. While fitting the epocs are set as 50. Loss function value initially is high but it reduces down and as set epoch 50 to get a better loss function value.

Plotly graphs are used for plotting the time series as you can see below

Close Price plotted: 
![image](https://user-images.githubusercontent.com/72770862/160303763-8a487d61-c14c-4257-98a1-6a745cd0c63c.png)

Result of LSTM Model: Red Line is Prediction and Green is the original closing value. 
![image](https://user-images.githubusercontent.com/72770862/160304207-7cc3238f-2a63-4ac5-bc6c-45ac3007bdc1.png)

Root Mean Square Error and R2 Score Values for LSTM Model: 
![image](https://user-images.githubusercontent.com/72770862/160304249-7d22d7c1-7d8e-49a6-874a-0508236c40f9.png)

**ARIMA Model**

I have used ARIMA(4,1,2) Model for forecasting the future values.
The predictions are as follows- 

ARIMA MODEL:
![image](https://user-images.githubusercontent.com/72770862/160304383-1324008c-6495-4773-aca8-6bcf1355597a.png)

Future 150 Days forecasting:

![image](https://user-images.githubusercontent.com/72770862/160304663-9088cfd5-0405-46c7-a8ef-8d7f173e5fcf.png)

Summary of ARIMA Model:

![image](https://user-images.githubusercontent.com/72770862/160304817-56aa7a32-92c4-444c-8d38-a93c7c75462a.png)

Forecasting Graph:

Forecasting plotted using plotly graph after taking inverse trasform of the predictions from the results of ARIMA Model

**Blue line indicates the forcasting values**


![image](https://user-images.githubusercontent.com/72770862/160304916-0c7f379f-e904-4f84-9f8a-0da475342cd5.png)

You can compare both and check LSTM and ARIMA. In this scenario I have used Tesla Stock but as I said the program will ask you initially which stock do you want to consider, you can enter the stock ticker value of your desired stock.


_**Thankyou**_

