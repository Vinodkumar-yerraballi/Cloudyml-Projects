# hackerearth_exhibit_art
#  Problem Statement  
To predict the cost required to ship the sculptures to customers based on the information provided in the dataset.
#  How will the company profit from this solution?
For the transport company having these kind of solution will help in many ways.
1. They can prioritize transports based on how reputated the artist is and how big the client is, because they don't want to mess with good paying clients.
1. They can do batch transports of the sculptures which are intended to go at same nearby location which will make the delivery cost less.
1. The company can't keep track which factor is making the cost vary more.
1. The cost is overall cost that company had to incur in order to ship the product. It's not something they can know before hand. There is no specific formula calculator the cost.
1. That's why they want a Data Scientist to look into past data and try to build some models which will predict the cost for future shipments.
1. So that accordingly they can ask the customers price that is profitable to them. 
1. If model is not in place then there maybe a chance of the company asking lower price for shipment while the actual cost of shipment for delivery was much higher. Thus they have a high chance of making lots of losses.
----------------------------------------------------
##Chi-square Test¶
1. The Chi Square statistic is commonly used for testing relationships between categorical variables.

2. The null hypothesis of the Chi-Square test is that no relationship exists on the categorical variables in the population; they are independent.

3. Example: Is there any significant relationship between gender and education qualification?

4. The Chi-Square statistic is most commonly used to evaluate Tests of Independence when using a crosstabulation.

5. Crosstabulation presents the distributions of two categorical variables simultaneously, with the intersections of the categories of the variables appearing in the cells of the table. that is values of one variable represents the row and other's value represents the column.

6. Formula: x^2 = Summation of( (observed value - Expected value)^2/Expected value )

7. The Chi-Square statistic is based on the difference between what is actually observed in the data and what would be expected if there was truly no relationship between the variables.

8. This statistic can be evaluated by comparing the actual value against a critical value found in a Chi-Square distribution (where degrees of freedom is calculated as of rows – 1 x columns – 1), but it is easier to simply examine the p-value.

9. To make a conclusion about the hypothesis with 95% confidence. Significance(p value of the Chi-square statistic) should be less than 0.05.

    1. Alpha level = 0.05(i.e 5%) 95% confidence about conclusion and 5% risk of not making a correct conclusion.

    2. Interpret the key results for Chi-Square Test for Association

        Determine whether the association between the variables is statistically significant.

        Examine the differences between expected counts and observed counts to determine which variable levels may have the most impact on association.
   
   ##Variance inflation factor (VIF)
1. The variance inflation factor (VIF) quantifies the extent of correlation between one predictor and the other predictors in a model. 
2. It is used for diagnosing collinearity/multicollinearity. 
3. Higher values signify that it is difficult to impossible to assess accurately the contribution of predictors to a model.

# Conclusion

We did training and prediction using all the above models and selected XGBRegressor Model as final model as it performed well compard to other models with acurracy of 99% on train data and around 96% on test data.

We did training and prediction using all the above models and selected RandomForrestRegressor Model as final model as it performed well compard to other models with acurracy of 99% on train data and around 95% on test data.

We did training and prediction using all the above models and selected GradientBoostingRegressor Model as final model as it performed well compard to other models with acurracy of 100% on train data and around 96% on test data.

According to this model, the predicted value we got,
matches with the actual target values. Does the model is performing well.

We have performed EDA, preprocessing, build different models, visualized feature importance, did hyper parameter tunning of each model and did prediction.
