# Portfolio
Data science portfolio.
Welcome to my data science portfolio! Please take a look around to get an idea of my Python and data science capabilities.

My current project is an attempt to predict violent crime rates based on income, metropolitan vs nonmetropolitan areas, and population size. The project is not complete, but it should show clear examples of data cleaning / preprocessing, feature scaling, multiple linear regression, support vector regression, random forest regression, XGBoost, and even a basic neural network. After testing these different models with a test set, I applied K-Fold Cross Validation to find the RMSE of the models. In the future I plan to also apply grid search to fine tune the models, but I am more focused in finding better predictive variables. If I find enough variables that dimensionality is an issue, I will apply backward elimination to select the most predictive features.

Right now none of the models are very predictive since the RMSE is about 250-300 for every model type in the k-fold validation. Using some data visualization techniques with SHAP plots, it's clear that there are a couple outliers that drastically impact the model accuracy, so those observations being chosen for the test or training set changes the output of the model. The SHAP plots show that those outliers change the model outcomes a lot but none of the other feature observations have much predictive power. The overall outcome of this project, so far, is that I am unable to accurately predict violent crime rates based on income, population size, and metropolitan area alone. More data will be needed and I will be updating this project in the future to attempt to better predict these violent crime rates.
