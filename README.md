# Time-Series-Forecasting-on-Chicago-bicycle-sharing-data
This Project shows the performance of ARIMA, VAR, and PROPHET Time series models on the Chicago Divvy Bicycle Data taken from the Amazon S3 bucket sourced at  https://divvy-tripdata.s3.amazonaws.com/index.html. Chicago, Illinois, has bikes available to rent all over the city called Divvy Bikes (https://divvybikes.com/). In this project, the data comes from the Chicago Divvy bicycle sharing system. The dataset contains 10 trip data years (2013 to 2023 November).

The trip data includes the following for each record:

1. the type of bike used, a classic pedal bike or pedal-assist electric bike

2. the start and end times of the trip

3. the start and end station information

4. the start and end GPS coordinates

5. the type of rider, member or casual rider

We have tried several approaches to the data to understand the various use cases and their solutions.

Preprocessing: Data is passed through a uniform pipeline for cleaning
Exploratory Data Analysis: To understand the crucial insights in the data
Feature Extraction: Suitable features used in classification and time series forecasting are generated here.
Mutual Information check: Analysing the data to determine whether it suits any classification or regression tasks.
Time Series Analysis: Univariate and Multivariate forecasts are based on the previous truth values, as this is sequential data.
