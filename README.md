# Car-Price-Predictor

#Aim
This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

# Description
### What this project does?
This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
It then predicts the possible price of the car. 

# How this project does?
First of all the data was scraped from Quikr.com (https://quikr.com)

The data was cleaned (it was super unclean :( ) and analysed.

Then a Linear Regression model was built on top of it which had 0.92 R2_score.

This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.
