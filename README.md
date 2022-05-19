# first_project
Diamond Price Prediction Project:
In this project, I train three models with Wesam Alsohle to predict the price of diamonds dependent on many features(weight, quality of the cut, clarity, length, width, depth,..., etc).
we follow some steps to train these models :
1- read the data from Kaggle (https://lnkd.in/eZMeYYb4).
2- visualize this data.
3-remove duplicate data or rows, faulty values( dimensionless[2-D or 1-D] diamonds ), and outliers using IQR.
4- apply ordinal encoder on categories data and data scaling 
5-model training[linera regression,decision tree,random forest]
6-fine tunning model(grid_search )

The RMSE ( Root Mean Squared Error) of the final model is 207.7491520515907.
