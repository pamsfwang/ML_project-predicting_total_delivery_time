# Predicting_total_delivery_time
This project aims to predict time needed to complete a food order request (in seconds). I have compared linear and nonlinear models with gridsearch approach and cross validation: Ridge, Lasso, and MLP models. The model with the least test error is the MLP model. The averaged trainning error for the MLP model is around 11 minutes (657 seconds).

## total_delivery_duration_prediction.ipynb
This notebook includes the codes for preprocessing data, model comparisons, and prediction.

## ML_funcs.ipynb
Machine learning functions used in 'total_delivery_duration_prediction.ipynb'. 
