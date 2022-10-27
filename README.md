# Demand_Forecasting_Application : Web based prototype application to forecast the demands

Important : Due to cache usage limitations on free hosting platoforms , this application is hosted locally & not on web servers . You can refer the PyCaret6.py file for accessing the code.

Shortages – Is one such word which every stakeholder in the supply chain industry comes across – be it a Buyer / Logistics Coordinator / Production Supervisor.

Shortages are inevitable , however those can certainly be reduced with the help of machine learning based forecasting models. 

Forecasting is an art of being less wrong , In this next use case of #SCMunfolds , I would like to showcase a prototype model for Demand Forecasting using Machine Learning.

This model compares various regression / time series techniques to predict the demands based on the historical data patterns predicting the best model to be used with highest level of accuracy amongst all.

Being a prototype , a very limited data is being displayed in this model , we can however explore it to the level desired.

You can upload a simple CSV file having date in first column & respective value in next consecutive column.

Library Used : PyCaret , PyCaret is a powerful library which has applications across TimeSeries , Classification & Regression

Input Screen : Select the slider to decide how many days of data you want to predict.

![HomeScreen](https://user-images.githubusercontent.com/66874304/198225932-bb16442d-0ca6-4a3c-8136-15560c8c2918.jpg)

No. of Days I have selected here are 30 , Click on 'Give a try with our example dataset' , model will start predicting the most suitable model.

![Selection Screen](https://user-images.githubusercontent.com/66874304/198227455-215630b2-0b9d-4b73-a496-505e3736f331.jpg)

Output matrix shows the comparison of performance of all the models :  Models having lowest error values are highlighted

![Model_Performance](https://user-images.githubusercontent.com/66874304/198236838-54105d19-a1b2-428c-bb61-916d22967215.jpg)


Output Screen : Based on the output of compariosn matrix : ARIMA model is the most suitable model for the example dataset . 
Plotting the values predicted by model on 'Test Data' . Predicted values are shown in Orange color

![Model_Performance_Plot](https://user-images.githubusercontent.com/66874304/198237455-f8bcaddc-ab80-4154-b7fd-7c5c9012b3fa.jpg)

Output Screen : As ARIMA has best accuracy , using this model to predict the future values . Future values are shown in Blue Color

![Output](https://user-images.githubusercontent.com/66874304/198228395-b7bb80da-2bf7-45fe-ab64-542295c3553f.jpg)


