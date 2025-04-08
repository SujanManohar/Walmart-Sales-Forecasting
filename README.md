# Walmart-Sales-Forecasting

Project Overview

This project focuses on forecasting Walmart's quarterly revenue, aiming to support decision-making regarding strategic planning and resource allocation. The analysis involves comprehensive exploratory data analysis (EDA) and utilizes advanced forecasting models to predict revenue trends.

Objectives

The primary goal of this project is to accurately predict Walmart's quarterly revenue using historical sales data, identifying seasonal patterns, trends, and appropriate forecasting models to facilitate data-driven business decisions.

Dataset
Timeframe: Q1 2009 - Q4 2024
Frequency: Quarterly
Measurement: Revenue in millions of dollars
Source: "Walmart Qtr.csv" provided in the project directory

Methodology:
The forecasting techniques employed include:
Exploratory Data Analysis (EDA):
Time series visualization
STL decomposition
Autocorrelation analysis (ACF)
Augmented Dickey-Fuller (ADF) Test for stationarity

Forecasting Models:
ARIMA (Auto-Regressive Integrated Moving Average)
Holt-Winters Exponential Smoothing (automatic parameter selection)

Model Evaluation Metrics:
Root Mean Square Error (RMSE)
Mean Absolute Percentage Error (MAPE)

Tools and Technologies
Programming Language: R
Libraries Used: forecast, zoo, dplyr, lubridate, ggplot2, tseries
Environment: RStudio

Results
The Holt-Winters Exponential Smoothing (automatic selection) was identified as the most accurate model based on lowest RMSE and MAPE scores:
RMSE: Lowest among tested models
MAPE: Lowest among tested models


This model was selected for generating final forecasts for future quarters.


