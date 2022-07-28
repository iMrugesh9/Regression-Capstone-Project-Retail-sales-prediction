# Regression-Capstone-Project-Retail-sales-prediction

Rossmann drug store chain operates over 3000 drug stores in 7 European countries. Historical sales data of the drug store chain of those stores can be used to predict the future sales depending upon the different features of those stores, like promotions, competition, school and state holidays, seasonality and locality.

For this study two sets of datasets were provided to predict the sales of any store. One dataset contained historical data including sales, and other dataset with supplement information about the stores. There were both numerical and categorical variables were in the dataset. Some columns having large amount of Null values were removed. Categorical variables were encoded with one hot encoding. Data were transformed to get the distribution as close as normal distribution, and finally standardized before training.

There were some challenges for the study. The size of the dataset was very huge. Some variables were not in ready to use form, conversion of the values of such columns were necessary for better usability. Particular models like knn, took a lot of time to train because of less feasibility with large dataset of the model.

In this study, different Machine Learning algorithms for supervised leaning for regression were used to build different models to predict the future sales of any particular store. Hyper parameters were tuned using GridSearchCV. Depending upon the highest metric value r2_score the best model was chosen. 
Finally KNeighborsRegressor model was chosen with n_neighbors=5 which produced highest r2 score.
