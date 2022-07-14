# Long-Short-Term-Memory-LSTM-Recurrent-Neural-Network-Wikipedia-Web-Traffic

Introduction
A Long Short Term Memory (LSTM) Recurrent Neural Network will be used to predict the number of visits (traffic) to the Wikipedia website. Each of the time series in the dataset represent a number of daily views of a different Wikipedia article starting from July 1st, 2015 until December 31st, 2016.

## Dataset
The source of the data is from Kaggle [link](https://www.kaggle.com/c/web-traffic-time-series-forecasting/data).

The dataset is a time series dataset with 145,063 entries and 551 columns. The dataset uses 609.8+ MB of memory! The original data contained two sets of data, but I was only able to work with one set because of the huge memory usage.

The dataset does not distinguish between traffic values of zero and missing values. A missing value may mean the traffic was zero or that the data is not available for that day. For accurate representation, any null value was imputed to the mean value of traffic/visits for that day.

There are 145,063 observations with 551 columns which represent the following:

Page (Article visited by all kinds of devices)
Dates from July 1, 2015 through December 31, 2016 (550 Columns).
