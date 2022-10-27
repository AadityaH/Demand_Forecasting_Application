# Demand_Forecasting_Application : Web based prototype application to forecast the demands

Shortages – Is one such word which every stakeholder in the supply chain industry comes across – be it a Buyer / Logistics Coordinator / Production Supervisor.

Forecasting is an art of being less wrong - better forecasting with machine learning models can certainly help in reducing the shortages to a great extent. 

In this next use case of #SCMunfolds , I would like to showcase a prototype model for Demand Forecasting using Machine Learning.

This model compares various regression / time series techniques to forecast the demands based on the historical data patterns predicting the best model to be used with highest level of accuracy among all.

Being a prototype , a very limited data is being displayed in this model , we can however explore it to the level desired.

Library Used : PyCaret , PyCaret is a powerful library which has applications across TimeSeries , Classification & Regression

Input Screen : Select the slider to decide how many days of data you want to predict.

![HomeScreen](https://user-images.githubusercontent.com/66874304/198225932-bb16442d-0ca6-4a3c-8136-15560c8c2918.jpg)

No. of Days I have selected here are 30 , Click on 'Give a try with our example dataset' , model will start predicting the most suitable model.

![Selection Screen](https://user-images.githubusercontent.com/66874304/198227455-215630b2-0b9d-4b73-a496-505e3736f331.jpg)

Comparison of performance of all the models :  Models having lowest error values are highlighted

![Model_Performance](https://user-images.githubusercontent.com/66874304/198236838-54105d19-a1b2-428c-bb61-916d22967215.jpg)


Output Screen : ARIMA model is the most suitable model for the example dataset . Plotting the values predicted by model on 'Test Data' . Predicted values are shown in Orange color

![Model_Performance_Plot](https://user-images.githubusercontent.com/66874304/198237455-f8bcaddc-ab80-4154-b7fd-7c5c9012b3fa.jpg)

Output Screen : As ARIMA has best accuracy , using this model to predict the future values . Future values are shown in Blue Color

![Output](https://user-images.githubusercontent.com/66874304/198228395-b7bb80da-2bf7-45fe-ab64-542295c3553f.jpg)


