* Executive Summary
In this project, I did explore the relationship between the SearchDate and HistCTR, relationship between the SearchDate and PriceAmount and did the visualisation by simple plot and histogram. By doing this part, I am able to find the click-through rate for ads in the time trend.
By exploring the relationship between userdeviceid and IsClick, the relationship between CategoryID and IsClick, I am able to find whether the Identifier of the category will influence visitors to click. 
In the next part, I use split the data into train data and test data, in order to do regression. 
Firstly, linear regression is applied to predict click rate by single variable price.
When the formula shown, we can know the price has negative effect on HistCTR.With comparison of RMSE, R2 and areaUnderROC, we can decide the effect of this model.
To predict, the variables CategoryID, AdID, IsUserLoggedOn, userdeviceid are used, and another linear regression model is done.
From the formula, the important variables are IsUserLoggedOn, IsClick
Secondly, we use classification algorithm, LogisticRegression and RandomForestRegressor, to predict whether visitors will click.


* Methods section, which provides details on the following:
    * How you sourced, ingested, cleansed, prepared the dataset with samples of intermediate data

I did not clean the data, and I just did visualization.

    * Tools you used for analyzing the dataset and the justification (tools, models, etc.)
Linear regression. LogisticRegression, and RandomForestRegressor

    * How did you model the dataset, what techniques did you use and why?
Firstly, linear regression is applied to predict click rate by single variable price.
With comparison of RMSE, R2 and areaUnderROC, we can decide the effect of this model. To predict, the variables CategoryID, AdID, IsUserLoggedOn, userdeviceid are used, and another linear regression model is done.

Secondly, we use classification algorithm, LogisticRegression and RandomForestRegressor, to predict whether visitors will click.

    * Did you have a hypothesis that you were trying to prove?
I want to test the effect of the three models(linear regression, logistic regression and randomForestRegressor).

* Challenges (technical & non-technical) and how you overcame them
I believe the challenges are to find the best model without overfitting. My solution is to compare the number of RMSE, R2 and ROC.

* Results/Conclusions section:
    * What did you find and learn?
When I did linear regression, the price has negative effect on HistCTR.
And the important variables are IsUserLoggedOn, IsClick

    * How did you validate your results?
I use RMSE, R2 and ROC to test the model.

* Future work: what would you do differently and what follow-up work would you do? Would you use other tools?
I believe I would like to try more methods, and think about the drawback and advantage of each method.

* Takeaways from the course
I believe this course gives me an insight of basic infrastructure of spark and hive, and by taking this course, I have my internship and start coding hivesql in daily job.

* Code files (you should list your code files here, and these must be in your submitted repository with appropriate comments.)
Project_YiyangSheng.ipynb is my python code.

