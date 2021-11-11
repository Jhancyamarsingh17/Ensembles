### Ensembles

This repository contains an example of a Ensemble models and model evaluation on the flight dataset.
### Dataset Description:
The objective of the dataset is to diagnostically predict whether or not a flight will be delayed, based on certain flight details included in the dataset.
### Business Question/ Steps done
Being able to understand the  features and classify into delayed or not delayed. 
Splitted the data into training/test sets
Inspected the data and createed a pipeline to perform any feature processing 
Fit a logistic regression, decision tree, and SVM using grid search and Discuss the performance of each model by Picking a metric roc- auc to select the model.
Fit an ensemble using the three above models. 
Fit a model using AdaBoost.
### Classification Results and Predictions
As it classifcation model , we cannot define the goodness of model using accuracy. So decided to be use aucroc score. 
Ada boost have proper model whereas tree has overffited. Tree performed good in training not in test. Ada boost increased the score by 6% from logistic regression
