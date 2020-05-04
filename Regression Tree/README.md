Hitters data set contains information on Major League Baseball from the 1986 and 1987
seasons. Among other information, it contains 1987 annual salary of baseball players
(in thousands of dollars) on opening day of the season. Our goal is the predict salaries
of the players. This data set is available from the ISLR package.

1. Remove the observations with unknown salary information. How many
observations were removed in this process?

2. Transform the salaries using a (natural) log transformation. Can you justify this
transformation?

3. Create a scatterplot with Hits on the y-axis and Years on the x-axis using all the
observations. Color code the observations using the log Salary variable. What
patterns do you notice on this chart, if any?

4. Run a linear regression model of Log Salary on all the predictors using the entire
dataset. Use regsubsets() function to perform best subset selection from the
regression model. Identify the best model using BIC. Which predictor variables
are included in this (best) model?

5. Now create a training data set consisting of 80 percent of the observations, and a
test data set consisting of the remaining observations.

6. Generate a regression tree of log Salary using only Years and Hits variables from
the training data set. Which players are likely to receive highest salaries
according to this model? Write down the rule and elaborate on it.

7. Now create a regression tree using all the variables in the training data set.
Perform boosting on the training set with 1,000 trees for a range of values of the
shrinkage parameter λ. Produce a plot with different shrinkage values on the xaxis and the corresponding training set MSE on the y-axis.

8. Produce a plot with different shrinkage values on the x-axis and the
corresponding test set MSE on the y-axis.

9. Which variables appear to be the most important predictors in the boosted
model?

10. Now apply bagging to the training set. What is the test set MSE for this
approach?
