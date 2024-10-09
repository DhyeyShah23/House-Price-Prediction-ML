# House Price Prediction using Linear Regression

This repository contains a simple machine learning model that predicts house prices based on the area of the house using a linear regression algorithm.

## Project Overview

In this project, we train a linear regression model on a dataset of house prices. The model is then used to predict the prices of other houses based on their areas.

### Dataset

- `homePricesData.csv`: Contains the area and corresponding prices of different houses, used for training the model.
- `homePricePrediction.csv`: Contains the areas of houses for which we want to predict the prices.

### Libraries Used

- `pandas` for handling datasets
- `numpy` for numerical operations
- `scikit-learn` for machine learning algorithms (linear regression)
- `matplotlib` for data visualization

### Code Explanation

1. **Load and Visualize Data**: We load the dataset and visualize it using a scatter plot to see the relationship between house area and price.
![image](https://github.com/user-attachments/assets/b42878ba-78d8-4a10-a41e-6068c9f2b6db)
![image](https://github.com/user-attachments/assets/5e34587f-a6d5-420f-92a5-38a615dc88c4)
2. **Train the Model**: We train a linear regression model using the areas and prices.
![image](https://github.com/user-attachments/assets/59c2f71b-4aaa-4231-b136-61606acec399)
3. **Make Predictions**: The model is then used to predict the prices of houses based on their areas from another dataset.
![image](https://github.com/user-attachments/assets/f8797744-9f26-46f7-b78b-e2201efb5c96)
4. **Save Predictions**: The predicted prices are added as a new column in the dataset.
![image](https://github.com/user-attachments/assets/76374939-7b0c-4d4d-bd56-35b06bad692f)



### THANK YOU!
