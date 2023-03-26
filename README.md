# UTSA 19: Supervised Machine Learning Challenge

## Background
### In this project, we are using data from lending services companies to create machine learning models to classify the risk level of loans. The data includes both personal loans and notes backing the loans on a secondary market.

## Approach
### We compared two models, Logistic Regression and Random Forest Classifier, to determine which one is better suited for this task. Our goal is to understand how other variables affect the risk level of the loans and determine whether or not a loan should be issued.

## Prediction
### Based on the data and analysis, we predicted that the Logistic Regression model would perform better than the Random Forest Classifier. This is because multivariate logistic regression is more suited than random forest classification for analyzing data with one nominal variable and multiple measurement variables.

## Results
### The Logistic Regression model performed better than the Random Forest Classifier, with data scores of 0.99 for both training and testing. The Random Forest Classifier had a perfect training data score of 1.0, but its testing score decreased to 0.76. Overall, the Logistic Regression model was better suited for supervised machine learning in this context.

## Recommendation
### We recommend using the Logistic Regression model for loan risk classification in this scenario. However, we also suggest exploring additional models and features to further improve the accuracy of the prediction.
