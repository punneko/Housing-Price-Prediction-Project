# Housing-Price-Prediction-Project
### Introduction
The goal of this project is to predict housing prices based on various factors, including area, bathrooms, air conditioning and other features. Accurately predicting housing prices is crucial for investors, home buyers, and sellers in making informed decisions in the real estate market. 

### Data Collection
The dataset used in this project was obtained from Kaggle's Housing Prices Dataset. The dataset consists of 545 rows and 13 columns, with features such as 'area', 'bathrooms', and 'air conditioning'. The target variable is 'price', which represents the price of the house.

### Model Selection
After performing EDA, I decided to use Linear Regression and Random Forest Regressor to compare evaluation both of them
1.Linear Regression Model: The R-squared value of 0.5667 indicates that Linear Regression explains approximately 57% of the variance in the housing prices, which is relatively low and suggests that the model does not capture all the patterns in the data. The MAE, MSE, and RMSE values show that the model's predictions are off by several hundred thousand dollars, reflecting the need for a more complex model to improve accuracy
2.RandomForest Model: The R-squared value of 0.5089 indicates that Random Forest explains approximately 51% of the variance in the housing prices. While this is slightly lower than Linear Regression, it still shows that the model is capturing significant patterns in the data. The MAE, MSE, and RMSE values suggest that the Random Forest model also has some room for improvement in terms of prediction accuracy.
