# Machine-learning-Stock-Predction
Using Linear Regression:
RMSE = 121.16291596523156
The RMSE value is high which clearly shows that linear regression has performed poorly.
Let’s look at the plot and understand why linear regression has not done well: As seen from
the plot above, for January 2016 and January 2017, there was a drop in the stock price. The
model has predicted the same for January 2018. A linear regression technique can perform
well for problems such as Big Mart sales where the independent features are useful for
determining the target value

Using KNN:
RMSE = 21115.17086550026721
There is not a huge difference in the RMSE value which clearly shows that knn has
performed poorly, but a plot for the predicted and actual values should provide a more clear
understanding.

Using LSTM:
RMSE = 11.772259608962642
We can clearly note that the RMSE value for this model is far less than the other two models. 
Hence we see that the graph is highly accurate for this model and appropriate for our problem
statement.
