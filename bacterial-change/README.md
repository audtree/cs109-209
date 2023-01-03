# Analyzing Top IMDB Stars

We began by scraping the HTML from the IMDB's webpage of the [Top 100 Stars for 2021](https://www.imdb.com/list/ls577894422/) using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/).

For analysis, we derived a variable for the approximate age of each star at the time of their first credit. This allowed us to identify child stars (first credit before age 11) and late bloomers (first credit after 26).  

# Predicting Bacterial Change

The goal of this assignment was to build regression models to predict the precent change in bacteria population after 4 hours based on their “spreading factor.” In this exercise, we consider the `spreading_factor ` to be our predictor variable and `perc_population` to be our response variable. We explore several different approaches, with mean squared error (MSE) as our evaluative criteria to find the best fit and most robust polynomial regression to model the relationship.

**Assignment outline:**
1. Guess best degree polynomial (3), fit to model
2. Calculate confidence intervals of coefficients
3. Find best-degree polynomial using a single validation set (illustrate overfitting)
4. Find best-degree polynomial using k-fold cross-validation
5. Find best-degree polynomial using k-fold cross validation with bootstraps
6. Improve model consistency with LASSO regularization <br />
     a. Use cross-validation to find regularization hyperparameter, alpha <br />
     b. Bootstrapping to find “most significant” set of polynomial degrees

