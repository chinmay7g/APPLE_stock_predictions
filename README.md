# APPLE_stock_predictions

The stock datasets or stock charts in the exchanges have the common attributes: Open, Close, High, Low, Adj.Close,Volume.
The attribute having the most influence in preditions is the 'Close' or the 'Adjusted close'. Adjusted Close means the closing price of the stock that day after taking into account all the corporate actions for that day.

Following repository aims at predicting the stock prices of the 'AAPL' stock from the NYSE using various algorithms. The more important lesson I have learnt from this is the conversion of the date format from string format ot the ordinal format.

![a4](https://user-images.githubusercontent.com/55191934/76598103-16923800-6528-11ea-83c7-5d6457f5747d.PNG)


Here is a glimpse of it's perfromance:

![a1](https://user-images.githubusercontent.com/55191934/76597740-29f0d380-6527-11ea-92b6-05a5766d7d36.PNG)


1. Linear Regression:

![a2](https://user-images.githubusercontent.com/55191934/76597775-40972a80-6527-11ea-96f4-7873e9e41abf.PNG)


![a3](https://user-images.githubusercontent.com/55191934/76597786-4a209280-6527-11ea-80ee-137022a9bf26.PNG)

The MSE value for this algorithm is 290.77 which is very high. And as it is evident from the graph also that the linear
model has failed to capture the trend effectively. And hence there arises such a huge MSE value. Since the linear model has
failed, we should move to non-linear models which can capture the trend.
