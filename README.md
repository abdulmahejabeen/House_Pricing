# House_Pricing
## Problem statement
The aim here is to predict the price a house using the given features
## Dataset
Features of a house and the price of the houses sold in Washington DC by a firm from May 2014 to May 2015.
## Data preparation
### Outlier Treatment using MICE:
The outliers are lookup row-wise and they accounted for 5.87% of the data, having at least one outlier in each row. As the percentage is significant enough to cause data loss if the rows are removed, they are treated using MICE.

## Modelling:
- Linear Regression
- Bagging
- Gradient Boosting.
  
As the linear regression model is not giving a good Adj.R-squared score. Among all the models built, Bagging and Gradient Boosting Algorithms were giving good Adj.R-squared scores.

## Dashboard Link:
https://public.tableau.com/app/profile/mahejabeenab/viz/Housepricesanalysiswashington/Housepricesanalysis
