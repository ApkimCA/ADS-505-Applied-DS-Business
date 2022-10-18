# The Automation of the Wine Selection Process

## Group Project: ADS 505 - Andrew Kim, Luis Perez, Renetta Nelson

## Project Objective

The purpose of this project is to automate the wine 
selection process in order to increase profit and build on the business's reputation. 
This will be done by implementing a model that predicts the quality of the wine.

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
