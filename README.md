# The Automation of the Wine Selection Process

## Group Project: ADS 505 - Andrew Kim, Luis Perez, Renetta Nelson

## Project Objective

From vendors to sommeliers, there are dozens of additional expenses when it comes to finding and 
purchasing good quality wine. The profits of the business can no longer support the expenses of the
wine selection process. Within a few months, the expenses will exceed profit and the business will have 
to close. Over half the profit of restaurant businesses come from wine, taking in approximately 70% of 
the total profit. Thus, the elimination of wine cannot not be a solution. The automation of the wine 
selection process will reduce the expenses, allowing the business to build its finances. 

## Wine Dataset

The dataset had the following predictors: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides,
free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol. The response variable was quality.

There were 1,599 rows with 12 columns. No missing data was present in this dataset. The response variable was split into two 
groups. The values of the predict variable that was 5 or less was changed to represent zero, which meant bad quality. The values
that were 6 or more were changed to 1, which meant good quality.

## Models Used in this Project

The following models were implemented: K-Nearest Neighbors (kNN), Linear Discriminant Analysis (LDA), Gradient Boosting, 
Logisic Regression, Random Forest, Decision Trees, and Neural Networks.

## Final Model Selection

The final model used was Random Forest, generating an accuracy level of 81 percent.
