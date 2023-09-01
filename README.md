# Data Analyst Portfolio - Audrey Chang

<img align="right" src="imgs/pp_circle.png" width="220">

Hi! I'm Audrey, an impact-oriented data scientist and Harvard junior joint concentrating in Statistics and Computer Science with a secondary in Sociology. This repository collects data science and data analysis projects I have completed for academic, self-learning and hobby purposes. 

**A bit about me...**

I love to work on projects that democratize knowledge, experience, and opportunity. 

In the last 3 years, I've...
* revitalized a public school district's hiring practices as an analyst [@Harvard College Economics Labs](https://www.harvardeconomics.org/), 
* contributed to 2 manuscripts in biological science [@Stanford](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4136719) and in materials science [@Harvard](https://bertoldi.seas.harvard.edu/), 
* designed useful and elegant digital experiences as a UI/UX consultant [@Harvard Design Collective](https://www.harvarddesignco.com/), 
* and spearheaded nationally-recognized environmental initiatives as co-president of [@Green Team](https://www.losaltosonline.com/schools/los-altos-high-earns-national-green-ribbon-for-sustainability/article_02a15773-37f6-5683-a195-b68b7572c40b.html). 

Talk to me about: applying data science, statistical & machine learning tools to business strategy, management, and marketing trends; the formation of community & social dynamics; and the design of products, places, and markets!

* **Email**: audreychang@college.harvard.edu
* **Linkedin**: [linkedin.com/audreyxychang](https://www.linkedin.com/in/audreyxychang/)

---
## Projects
<sup> Note: Some projects are associated to coding exercises and assignments from Harvard's Data Science course, CS109. It violates Copyright Laws to have the assignments available publicly, although I am happy to walk through a detailed project process upon request — see my contact information below! When available, a summary of my produced figures is linked in the associated repository's README. </sup>

---
### Analyzing Top IMDB Stars

Scraped the HTML from a webpage of [Top 100 Stars for 2021](https://www.imdb.com/list/ls577894422/) using the BeautifulSoup Python package and stored actor/actress profiles in a JSON file. Loaded data into dataframe to calculate new actor/actress metrics (age at first credit, number of credits), summary statistics (number of child stars, number of late bloomers), and explored how profiles differed between age groups and genders.  

**Skills:** web scraping, data parsing, EDA <br />

---
### Analyzing Social and Economic Supplement Dataset 

Analyzed simulated income data from the publically available 2021 US Annual Social and Economic (ASEC) Supplement ([source](https://www.census.gov/data/datasets/time-series/demo/cps/cps-asec.2021.html)), provided by the US Census Bureau. (Simulated data turns discrete response variable to continuous response variable via sampling.) Visualized distribution of income by gender, occupation type, education across gender, industry, age, marital status, and of time worked and wage. Calculated Gini coefficient to [measure inequality](https://en.wikipedia.org/wiki/Gini_coefficient) and compared coefficient to other countries. 

**Skills:** data visualization, EDA <br />

---
### [Predicting change in bacteria populations](https://github.com/audtree/data-analyst-portfolio/blob/main/bacterial-change/README.md)

Built regression models to predict the percentage change in bacteria population after 4 hours based on their "spreading factor." Used k-fold cross validation and boostraps to identify the best degree polynomial regression and LASSO regularization with hypermarameter tuning to improve model consistency and identify the "most significant" set of polynomial degrees by using bootstraps.

**Skills:** LASSO regularization, polynomial regression, model selection, hyperparameter tuning, data visualization <br />

---
### Predicting the selling price of cars with missing data

Analyzed [Kaggle data](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho), pre-processed and modified so that it contains missing values, to predict the selling price of used cars with a linear regression model and kNN regression model. Imputed missing data with a simple mean and verified that our prediction strategy was not affected by imputation by re-fitting models with missing indicator variables. The dataset is pre-processed and modified so that it contains missing values. The goal is to handle missing data and predict selling prices from the other features available in this dataset.

**Skills:** linear regression, k-Nearest Neighbors (kNN) regression, hyperparameter tuning <br />

---
### Predicting college admissions

Used data scraped from [collegedata.com](collegedata.com) — around 1500 students with 16 features each — to fit a logistic regression and kNN classification models to predict admittance into Harvard and Yale based on student characteristics. Employed Lasso-like logistic regression model to determine and restrict the training data to important predictors; refit and compared classification models via their ROC curves. 

**Skills:** logistic regression, ROC curves & AUC metric

---
### Classifying Higgs bosons

Examined data from Monte-Carlo simulations of collisions of particles in a particle collider experiment (subset of HIGGS data set in the UCI machine learning repository, details [linked](https://www.nature.com/articles/ncomms5308)) to classify which collisions produce Higgs bosons. The data contain 5000 entries, each a particle collisions described by 28 features. Constructed baseline prediction model from an overfit decision tree. Employed bagging model to reduce variance, random forest model to reduce correlation between trees, and an AdaBoost classifier to further improve accuracy. With AdaBoost Classifier, explored validation and training accuracy as a function of number of estimators and base learner depth.  

**Skills:** boosting (AdaBoost), random forests, bagging

---
### Predicting homelessness rate

Built a model that predicts the total number of individuals experiencing homelessness per 10,000 people in the US based on environmental and market predictors using [data](https://www.huduser.gov/portal/datasets/hpmd.html) from the US Department of Housing and Urban Development (HUD). Expanded upon the HUD's 2019 report and reconstructed their linear regression predictive model as our baseline model. Cleaned data, conducted exploratory data analysis and visualization for selected features. Developed model: implemented decision tree model with cross validation, bagging model with cross validation, random forest model, AdaBoost and gradient boosting models, and a stacked model. Compared models via their R-squared values and computation time to determine that the Gradient Boosting model performed the best on the test data with the highest $R^2$ value of 0.8859, far greater than the simulated report linear regression with an $R^2$ of 0.385. 

**Skills:** model stacking, AdaBoost, gradient boosting, model selection, random forest, data visualization, data cleaning and imputation

## Core Competencies

* Supervised Learning
    * kNN
    * Linear Regression
    * Regularization
    * Logistic Regression
    * Decision Trees, Bagging, and Random Forests
    * Gradient and Adaptive Boosting
* Unsupervised Learning
    * K-Means Clustering
    * PCA
* Data Collection & Management
    * Imputation
    * Web scraping
    * Data Ethics
    * Data Visualization

## Work in Progress

In Spring 2023, I will be taking [AC209b: Advanced Topics in Data Science](https://harvard-iacs.github.io/2020-CS109B/pages/syllabus.html). Topics include:
* Smoothing and Additive Models
* Unsupervised Learning, Clustering
* Bayesian Modeling
* Convolutional Neural Networks
* Autoencoders
* Recurrent Neural Networks
* NLP / Text Analysis
* Variational AutoEncoders & Generative Models
* Generative Adversarial Networks
* (Deep) Reinforcement Learning

<!---
In my free time, I am currently exploring a [fictional dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) of Employee Attrition & Performance created by IBM data scientists and provided by Kaggle. I use this data to build a model that predicts the likelihood of attrition dependent on specific employee characteristics, identifying significant factors that contribute to attrition. I will update my Github with work when complete. 
-->
