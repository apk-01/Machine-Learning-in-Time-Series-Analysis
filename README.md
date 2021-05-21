# Machine-Learning-in-Time-Series-Analysis

The repository explores machine learing techniques for analysing time series data. 

We shall focus on:

1. Trend analysis, seasonal decomposition and auto correlation function.
2. Forecasting of confirmed cases using ARIMA model. 

Dataset used: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv

The codes are written on : google colaboratory (https://colab.research.google.com/notebooks/intro.ipynb)

To execute the codes locally:

1. Set up anaconda
2. Add python 3.6+
3. Remove google colab file uploading cell from the notebook
4. Install the dependencies(imported libraries) before executing the program
5. Execute the code with your own data/images

To execute with google colab:

1. Upload your own data/images while executing the upload cell
2. Replace the file reading file names with your image file names
3. Execute the remaining cells

![time_series](/images/Seasonality.png)

# Trend analysis, seasonal decomposition and auto correlation function

We shall plot the total confirmed cases, determine the trend and seasonality factor using the seasonal decomposition and Auto correlation function. We shall also make our data stationary by differentiating and verify the same by the Augmented Dickey Fuller function.

# Forecasting of confirmed cases using ARIMA model

Auto-Regressive Integrated Moving Average (ARIMA) and Seasonal Auto-Regressive Integrated Moving Average (SARIMA) are used to forecast the epidemiological trends of the COVID-19. The model parameters were selected using the auto-ARIMA model based on AIC value minimization. 
