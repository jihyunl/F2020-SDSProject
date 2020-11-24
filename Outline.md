# Outline

## Method:

* Describe method

### Shrinkage approaches
1. Ridge regression

> Remove? (JL)

2. Lasso

> How to choose lambda? -> Use cross validation

> Do we need to use only training dataset?


### Regression tree

1. Pruning a tree

2. Variable importance measure


## Results

Model fit

Model fits (Cp, AIC, BIC, Adjusted R2)

Cross Validation (K-fold or LOOCV)

> Q: How can we compare LASSO vs. Tree model?

- Predictive performance -> distribution of the error. -> No need to have AIC/BIC. 
- Check the trees - which variable is the most important. whether the same predictor is selected from LASSO.
- Ensemble method for trees -> variable importance measure. 
- out of sample error.from cross validation.
- Try to use the same train/test division to check for two approaches.
