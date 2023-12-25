# Situation:
The goal of this project is to predict house prices using PCA and a supervised machine learning model. The use of PCA is mandatory because the dataset contains 81 columns.
# Actions:
I first familiarized myself with the dataset and the project's goal by displaying statistical information about the dataset. 
Then, I removed the unnecessary column such as 'Id' and split the data into 'X' and 'Y,' where 'X' represents the columns that will be used to predict 'Y,' which is the 'SalePrice' column. 
I excluded categorical data because PCA only works with quantitative data. After that, I split the data into a training set and a test set and performed necessary preprocessing using sklearn, such as filling in missing values in the dataset. Following this, I trained the RandomForestRegressor model and displayed its score.

Subsequently, I normalized the data and applied PCA to reduce the number of columns from 33 (excluding categorical columns) to 3 columns. Then, I trained the same model using the PCA-transformed columns, which contain approximately 35.68% of the information from the original data.

P.S.: I did not normalize the data before using PCA because tree models can work with non-normalized data! 
# Results:
The model is almost as performant with 3 columns as it is with 33! 
