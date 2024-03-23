## Project Description
A used car sales service is developing an app to attract new clients, allowing them to quickly determine the market value of their car. The project aims to build a model based on historical data to predict a car's price.

## Objectives
The primary objective is to develop a car price recommendation system based on the car's description, focusing on:
- Prediction quality.
- Prediction speed.
- Training time.

## Skills and Tools
- python
- pandas
- numpy
- matplotlib
- seaborn
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.OneHotEncoder
- sklearn.preprocessing.StandardScaler
- lightgbm.LGBMRegressor
- sklearn.ensemble.RandomForestRegressor
- sklearn.metrics.mean_squared_error
- time

## General Conclusion

In this project, I evaluated RandomForestRegressor and LightGBM models, focusing on optimized parameters for speed and accuracy. My findings are:

- **RandomForestRegressor** showed high accuracy with an RMSE of 1629.71 but took longer to train.
- **LightGBM** was slightly less accurate with an RMSE of 1654.88 but significantly faster in training and prediction times.

Given these outcomes, I concluded LightGBM to be the preferable model for this application, balancing speed and accuracy effectively
