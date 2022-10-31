## Variable Selection
Finding the best possible subset of variables to put in a model has been a frustrating exercise. Many variable selection methods exist. I would ideally start with 
### Forward selection on a linear or logistic regression model
Forward selection is a type of stepwise regression which begins with an empty model and adds in variables one by one. In each forward step, you add the one variable that gives the single best improvement to your model.
### Backward selection on a linear or logistic regression model
In backward selectionyou start with a model that includes every possible variable and eliminate the extraneous variables one by one
### Bidirectional elimination (Stepwise (SW) )
A combination of the above( forward and backward), testing at each step for variables to be included or excluded.
### All-possible Subsets 
This method builds all one-variable models, all two-variable models,and so on, until the last all-variable model is generated. The method requires the selection of any one of the criteria:
R-squared, adjusted R-squared or Mallows ’ Cp. 
### Criterion Based Selection
If there are p potential predictors, then there are 2p possible models. We fit all these models and choose the best one according to some criterion. Some criteria are
#### The Akaike Information Criterion (AIC) and the Bayes Information Criterion (BIC)
The model with the lowest AIC or BIC criterion is then selected
#### Adjusted R2 
The model with the Highest adjr2 criterion is then selected
#### Predicted Residual Sum of Squares (PRESS)
The model with the lowest PRESS criterion is then selected
#### Mallow’s Cp Statistic.
We can identify the “best” regression model by identifying the model with the lowest Cp value that is less than P+1, where P is the number of predictor variables in the model.
### Penialized linear Regression
Penalized regression methods keep all the predictor variables in the model but constrain (regularize) the regression coefficients by shrinking them toward zero. If the amount of shrinkage is large enough, these methods can also perform variable selection by shrinking some coefficients to zero. When shrikage is 1 itis called LASSO and when it is 0 it is called Ridge. Any value between 1 and 0 is Elastic.
### Multiple Regression with interaction and polynomial terms
Multiple linear regression (MLR), also known simply as multiple regression, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. Multiple regression is an extension of linear (OLS) regression that uses just one explanatory variable.
## Summary
It is extremely important to include appropriate variables in prediction modelling, as model’s performance largely depends on which variables are ultimately included in the model. Failure to include the proper variables in the model provides inaccurate results, and the model will fail to capture the true relation that exists in the data between the outcome and the selected variables. 
In my opnion all the listed methods should be tested on a training dataset and applied to the test dataset. Out of all models the best model should be selected.
Ideally for me the model with the least square regression is the best model fit.
