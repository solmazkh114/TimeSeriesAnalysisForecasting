# Time Series Analysis and Forecasting

This directory contains a notebook aims to explore time series concepts in data analysis and time series forecasting. During this investigation, we will use 
[Darts](https://github.com/unit8co/darts) library which is a powerful library for forecasting and time series analysis in Python. It stands out due to its simplicity, flexibility, and high-performance capabilities, making it a popular 
choice for time series forecasting tasks. Darts includes a wide range of forecasting models such as ARIMA, Exponential Smoothing State Space Models (ETS), Prophet, Theta, NBEATS, and machine 
learning models like Linear Regression, LightGBM, XGBoost, and more. Darts allows users to work with various types of covariates, including past, future, and static covariates, in conjunction
with different forecasting models. Moreover, it suports multivatiate time series as well as multiple time series at once. 

Darts is built on top of several Python libraries including, Numpy, Pandas, Matplotlib, Stats and PyTorch. 

To install darts one can use the usuall pip command:

```pip install darts```

This way of installion will not install all avaialbel models, so one can use the commands [here](https://github.com/unit8co/darts/blob/master/INSTALL.md). 

Most of codes I learned and worked with in this notebook come from the fantastic Darts' [notebook examples](https://unit8co.github.io/darts/examples/01-multi-time-series-and-covariates.html).

In this notebook, we will explore different ways of loading time series data with Darts and will end it with model training on some real time series data from a large Ecuadorian-based grocery 
retailer. This is the [link](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview) of this dataset on Kaggle. The whole process on this dataset including extensive data analysis and model traning can be find in this [Repo](https://github.com/solmazkh114/Sales-Data-Forecasting.git).
