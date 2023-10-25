# Supply_Chain IOT assignment
# Sales Forecasting with Historical Data

This project aims to predict sales for SKU (Stock Keeping Unit) and store combinations using historical sales data for the past 3 years on a week-on-week basis. The data includes sales, promotional seasonality, SKU information, and store information.

## Project Overview

- We have two datasets:
    - Traindata.csv: Historical sales data used to train the forecasting model.
    - DataSetRetail.csv: Data on which we want to make predictions.

- Predictive Model: We use Holt Winters, linear regression and other such models.

- Predictions: The model generates predictions for the next 12 weeks for each SKU and store combination.

## Code

- sales_forecasting.ipynb: A Jupyter Notebook that contains the Python code for data loading, preprocessing, modeling, and making predictions. The code is well-documented and organized.

## Results

- The predictions are saved in a CSV file named predictions.csv, which follows the submission format required for the task.

## Issues Faced

- One of the main challenges was dealing with seasonality, especially for SKU and store combinations where the seasonality pattern may vary significantly.

- An initial challenge was related to data preprocessing, including handling missing values and setting up the dataset for time series forecasting.

- In the absence of additional information regarding stores and products, some product/store combinations may have better forecasting accuracy than others due to differences in historical data quality.

## Next Steps

- To improve forecasting accuracy, one could explore more advanced time series models, feature engineering, or additional data sources.

- Explore other forecasting models and techniques to identify which one works best for different product/store combinations.

## How to Run the Code

- Install Python and Jupyter Notebook.
- Execute the code cells in order to load the data, train the model, and make predictions.


