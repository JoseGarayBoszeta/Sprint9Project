**Project Description**<br>
This project analyzes 3 regions of possible implementation of new oil wells for the mining company OilyGiant.<br>
The project consists of developing Machine Learning models to predict the productivity of each region, and thus evaluate the viability of implementing new oil wells.<br>
Taking into account the historical production dataframes of each region, we train several regression models using LinearRegression and RandomForest algorithms.<br>
We then evaluated their performance using the MSE, RMSE, MAE and R2 Score metrics. After the model analysis, we take into account the average cost of implementing new oil wells ($100M USD for 200 oil wells), and evaluate the profitability of each Region according to the predictions of each model. For this we will use the Bootstrapping technique, taking random samples of 500 points and selecting the 200 most productive points of each sample.<br>
Finally, we calculate the average production of each region within a 95% confidence interval, indicating the minimum and maximum intervals (2.5% and 97.5%).<br>
