# house-prices-python
Predicting House prices in Seattle with Python and Jupyter notebooks
You can see the project in my personal website https://www.datascientist.cz/portfolio/predicting-house-prices-with-python-and-jupyter-notebooks/
ABOUT THE PROJECT
This is a simple project that analizes a dataset of house prices in Seattle and identifies the variables that are more correlated with prices. Then several regression models are applied and the R^2 of each model is tested.

DATA SOURCE
The data were provided by IBM as a part of the Data Science Professional Certificate . 

RESULTS
The best results to predict the prices of houses were obtained using a linear regression model with StandardScaling and PolynomialFeatures. The R_squared parameter for this model was = 0.75. Since many input variables were autocorrelated, Ridge Regression was also tested, but the results were not as promising as with the mentioned combination (R_squared =0.70).
