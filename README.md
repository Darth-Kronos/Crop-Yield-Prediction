# Crop-Yield-Prediction :seedling:

## Description

Crop yield prediction remains one of the most challenging tasks in agriculture as it affects decision making at global, regional, and field levels. The prediction of crop yield is based on several factors such as soil, meteorological, environmental, and crop parameters. Due to the colossal effect agriculture has on the economy of the country, data-driven prediction models need to be developed. Against this background, machine learning (ML) models were engineered after processing agricultural data and Regression models were deployed to predict the yield. The developed models were then compared with each other to obtain the best performing model.

## Dataset

The yield data with corresponding fertilizer usage and export quantity data obtained from the FAOSTAT database was combined with pertaining to the climatic conditions of each year, obtained from Climate Change Knowledge portal and 4 features, namely - Precipitation, Temperature (avg), Export Quantity, and Fertilizer Used were used to train the ML models.

## ML Models 
In order to predict the crop yield for each crop, regression models were deployed, whose task is the prediction of the dependent variable with the help of other independent variables. Keeping ‘Crop’ as the ground truth value along with the 4 feature columns, five regression models, namely - Multivariate Linear Regression, Shrinkage methods (Ridge and Lasso regression), k-nearest neighbors, Decision Tree and Artificial Neural Networks were trained.

Against the optimum performance standards for this task, after observation and evaluation of the metrics of the regressors, Decision Tree regressor exhibited best performance.

The analysis thus retrieved can be used as a basic prototype by the agricultural industry for further research by using better data, advanced pre-processing techniques and machine learning models.


