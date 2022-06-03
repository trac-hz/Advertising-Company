# Big Data Project

* Executive Summary
In this project, I did explore the relationship between the SearchDate and HistCTR, relationship between the SearchDate and PriceAmount and did the visualisation by simple plot and histogram. By doing this part, I am able to find the click-through rate for ads in the time trend.
By exploring the relationship between userdeviceid and IsClick, the relationship between CategoryID and IsClick, I am able to find whether the Identifier of the category will influence visitors to click. 
In the next part, I use split the data into train data and test data, in order to do regression. 
Firstly, linear regression is applied to predict click rate by single variable price.
When the formula shown, we can know the price has negative effect on HistCTR.With comparison of RMSE, R2 and areaUnderROC, we can decide the effect of this model.
To predict, the variables CategoryID, AdID, IsUserLoggedOn, userdeviceid are used, and another linear regression model is done.
From the formula, the important variables are IsUserLoggedOn, IsClick
Secondly, we use classification algorithm, LogisticRegression and RandomForestRegressor, to predict whether visitors will click.
