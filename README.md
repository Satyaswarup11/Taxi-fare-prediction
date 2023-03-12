# New York Taxi-Fare Prediction

This project aims to predict the taxi fares of New York using linear regression. The dataset was taken from Kaggle.

## Dataset
The dataset used in this project contains information about taxi rides in New York, including pickup and dropoff locations, number of passengers, and fare amount.

## Preprocessing

Before building the linear regression model, the dataset underwent some preprocessing steps. These included:

* Removing rows with missing values
* Removing rows with fare amount less than $2.5 or greater than $200 (to remove outliers)
* Removing rows with passenger count less than 1 or greater than 6 (to remove outliers)
* Converting the pickup datetime to separate columns for year, month, day, hour, and minute.


## Model Building
The model was built using linear regression. The model takes in the pickup and drop-off locations, the pickup datetime, and the passenger count as input and predicts the fare amount.

The model was trained on 80% of the dataset and tested on the remaining 20%. The mean squared error (MSE) was used as the evaluation metric.

## Results
The results of the model show a strong correlation between the input features and taxi fares. The model can be used to predict fares for new taxi rides with a reasonable degree of accuracy.

## Usage 
To use this project, simply clone the repository and run the taxi_fare_prediction.ipynb notebook. This notebook contains the code for preprocessing the dataset, building the linear regression model, and evaluating the model.

## Conclusion
This project demonstrates the use of linear regression to predict taxi fares in New York. The model can be used to help taxi companies optimize their pricing strategies and provide more accurate fare estimates to customers.With further improvements to the preprocessing steps and feature engineering, the model's accuracy could be improved even further.

