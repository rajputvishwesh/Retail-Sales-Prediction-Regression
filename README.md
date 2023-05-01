# Retail-Sales-Prediction-Regression
Project Overview
This project is aimed at predicting the daily sales for the Rossman stores for up to six weeks in advance. The data includes the historical sales data for 1,115 Rossmann stores. The objective is to forecast the "Sales" column for the test set.

Tools Used
Python 3
Jupyter Notebook
Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
Data Description
The data includes two datasets: Rossmann and Store. There are 1,017,209 rows and 9 columns in the Rossmann dataset, and 1,115 rows and 9 columns in the Store dataset. After merging the datasets, there are 1,017,209 rows and 18 columns. There are no duplicated rows and columns, but there are duplicated values. The Store dataset contains missing values.

Project Steps
Data Cleaning and Data Wrangling: Merging both tables and handling missing values and null values.
Exploratory Data Analysis (EDA): Creating different visualization charts to analyze the data, identifying correlations between variables and identifying interesting facts.
Hypothetical Testing: Conducting a two-sample t-test to test the hypothesis that stores located closer to competition have significantly lower sales than stores located further away.
Feature Engineering: Filling missing values, handling null values, handling columns, deleting unnecessary columns, feature processing, feature extracting, outlier handling, and feature selection.
Model Deployment: Deploying two regression models, Linear Regression and Lasso Regression, and comparing their performance using evaluation metrics like mean squared error (MSE) and R-squared (R2) score.
Conclusion
The project's objective was to predict the daily sales for the Rossmann stores for up to six weeks in advance. The Linear Regression and Lasso Regression models both have very similar performance, with the Lasso Regression model having a slightly lower MSE and a slightly higher R2 score. The mean squared error (MSE) measures the average squared difference between the predicted and actual values, where a lower MSE indicates better performance. The R-squared (R2) score measures the proportion of the variance in the dependent variable that is predictable from the independent variables, where a higher R2 score indicates better performance.

Acknowledgements
This project is a part of the Retail Sales Prediction challenge on Kaggle. The data is provided by Rossman, and the challenge is hosted by Kaggle.
