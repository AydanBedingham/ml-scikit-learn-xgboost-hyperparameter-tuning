# Hyperparameters Optimization for ScikitLearn XG-Boost
Jupyter Notebook that uses Scikit-Learn to to train a machine learning model to predict the MSRP (Manufacturer's Suggested Retail Price) for cars using a 'used car prices' dataset. Trains an XGBoost model and compares the non-optimised RMSE and R2 values to those obtained using GridSearch for hyperparameter tuning.

- Tasks:
    - Load the “used_car_price.csv” dataset
    - Split the data into 75% for training and 25% for testing
    - Train an XG-Boost model and obtain the RMSE and R2 values (No optimisation)
    - Perform GridSearch hyperparameter optimization and obtain the RMSE and R2 values
