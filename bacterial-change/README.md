# Predicting Bacterial Population Growth

The goal of this assignment was to build regression models to predict the precent change in bacteria population after 4 hours based on their “spreading factor.” In this exercise, we consider the `spreading_factor ` to be our predictor variable and `perc_population` to be our response variable. We explore several different approaches, with mean squared error (MSE) as our evaluative criteria to find the best fit and most robust polynomial regression to model the relationship.

**Skills:** LASSO regularization, polynomial regression, model selection, hyperparameter tuning, data visualization
**Tools:** scikit-learn

**Assignment outline:**
1. Guess best degree polynomial (3), fit to model
2. Calculate confidence intervals of coefficients
3. Find best-degree polynomial using a single validation set (illustrate overfitting)
4. Find best-degree polynomial using k-fold cross-validation
5. Find best-degree polynomial using k-fold cross validation with bootstraps
6. Improve model consistency with LASSO regularization <br />
     a. Use cross-validation to find regularization hyperparameter, alpha <br />
     b. Bootstrapping to find “most significant” set of polynomial degrees

---

**1. Guess best degree polynomial (3), fit to model**

We began by visualizing the predictor and response variable in a simple scatter plot. Based on a visual inspection of the data, we estimate the degree of a polynomial we believe would best fit the training while still generalizing well. The data are shown below, with a fitted degree-3 polynomial. 

<p align="center">
  <img src="imgs/initial-model.png" />
</p>

**2. Calculate confidence intervals of coefficients**

<p align="center">
  <img src="imgs/CI-coefficient.png" />
</p>

**3. Find best-degree polynomial using a single validation set (illustrate overfitting)**

**4. Find best-degree polynomial using k-fold cross-validation**

<p align="center">
  <img src="imgs/train-val-MSE.png" />
</p>

<p align="center">
  <img src="imgs/best-degree-polynomial.png" />
</p>

**5. Find best-degree polynomial using k-fold cross validation with bootstraps**

<p align="center">
  <img src="imgs/bootstrapping.png" />
</p>

**6. Improve model consistency with LASSO regularization**

Use cross-validation to find regularization hyperparameter, alpha

<p align="center">
  <img src="imgs/mean-val-MSE.png" />
</p>

b. Bootstrapping to find “most significant” set of polynomial degrees


<p align="center">
  <img src="imgs/bootstrapping-pt2.png" />
</p>

Final model comparison

<p align="center">
  <img src="imgs/comparing-latter-models.png" />
</p>

<p align="center">
  <img src="imgs/comparing-model-MSE.png" />
</p>
