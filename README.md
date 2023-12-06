# Car Price Predictor

<img src="https://github.com/HalfBloodBunny/Car-Price-Prediction/blob/main/demo.png">



# Aim

This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

<img src="https://github.com/HalfBloodBunny/Car-Price-Prediction/blob/main/predict.png">

## How to use?

1. Clone the repository
2. Install the required packages in "requirements.txt" file.

Some packages are:
 - numpy 
 - pandas 
 - scikit-learn

3. Run the "application.py" file
And you are good to go. 

# Description

## What this project does?

1. This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car. For example, the image below shows the predicted price of our Hyundai Grand i10. 

<img src="https://github.com/HalfBloodBunny/Car-Price-Prediction/blob/main/predict.png">

## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com).
Link for data: https://github.com/HalfBloodBunny/Car-Price-Prediction/blob/main/quikr_car.csv

2. The data was cleaned

3. Then a Linear Regression model was built on top of it which had 0.84 R2_score.

Link for notebook: https://github.com/HalfBloodBunny/Car-Price-Prediction/blob/main/CarPricePrediction.ipynb

4. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

