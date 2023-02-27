# UTSA 20: Supervised Machine Learning Challenge

## Background

#### Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

## Prediction

#### Prediction: Based on the data and the requested analysis, I would predict that the logistic regression would be a better model.

Rationale: Multivariate logistic regression is more suited than random forest classification to analysis involving one nominal variable and two or more measurement variables.

Application: In this case, our goal is to know how or whether other variables affect the nominal variable to determine whether or not a loan should be issued.

## Conclusion

#### Conclusion: At data scores of 0.99 for both training and testing, as predicted the logistic regression model is better suited for supervised machine learning in this context than the random forest classifier.

While the random forest classifier's training data score was a perfect 1.0, in actual testing its score decreased to 0.76.  While this is still considered a good result for a data score, this result is not as strong as the logistic regression model's.
