# UsedCarPrediction
## Project description
This project involved exploring the dataset provided here on kaggle: https://www.kaggle.com/datasets/harikrishnareddyb/used-car-price-predictions
and the develop a machine learning model to predict the price of used cars based on the provided dataset. 
The beginning of the project involes EDA where the different features are explored and visualized.
Moving on outliers are removed and additional features are derived from the provided columns.
At the end of the project the actual machine learning model is developed.
I tried a multitude of machine learning models, but XGBOOST regression performed the best.
In order to use the XGBOOST regression model the categorical features where encoded using LabelEncoding.
I choose LabelEncoding instead of OneHotEncoding to prevent a sparse matrix to form due to the many different categories with many different values in them.
To achieve a better rmse score for my XGBOSST model I did hyperparameter tuning. 
The rmse achieved is not the best and there is definitely room for improvement, either by improving the existing model or trying deep neural networks instead.
