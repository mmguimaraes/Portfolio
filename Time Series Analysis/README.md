# SARIMA model applied to CO<sub>2</sub> and CH<sub>4</sub> data collected at Mauna Loa Observatory. 

SARIMA stands for Seasonal Autoregressive Integrated Moving Averages and it is a very useful technique applied to time series analysis, specially with the data presents seasonality.

We will take a look at the data collected at the Mauna Loa Observatory, in Hawaii, for two important Greenhouse gases: CO<sub>2</sub> and CH<sub>4</sub>. 

The data was retrieved from the Earth System Research Laboratory (ESRL) Global Monitoring Division website: <a href='https://www.esrl.noaa.gov/gmd/dv/data/index.php'>ESRL/GMD Data Finder.</a> 

If you want to know more about SARIMA, take a look at:
<a href='https://www.statsmodels.org/stable/statespace.html'>Statsmodels Tutorial</a>

### Author: Marcelo M. Guimarães
### Date: 2020-04-02
### email: mguimaraes@protonmail.com

# Using SARIMAX

## Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors

In this case we will deal with an external factors and see how it can influence a time series and forecasting.

## The data:

We will use a dataset build during a recent Udemy Data Science Course on Time Series Analysis. The Udemy course can be viewed <a href='https://www.udemy.com/course/python-for-time-series-data-analysis/'>here.</a>

It is a Restaurant Visitors dataset, inspired by a two years old <a href='https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting'>Kaggle competition</a>. The original competition consisted on predictions for future costumers for Japanese Restaurants. The current dataset considers daily visitors to four restaurants located in the United States, subject to American holidays. 

Our exogenous variable will be the American holidays. The dataset contains 478 days of restaurant data, plus an additional 39 days of holiday data for forecasting purposes.

### Author: Marcelo M. Guimarães
### Date: 2020-04-07
### email: mguimaraes@protonmail.com
