# Car Price Predictor

Project link: 

# Aim

This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

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

## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com) . 

2. Cleaning of data as it was super unclean in the beginning .

3.Analysis of data .

4. Then a Linear Regression model was built on top of it which had 0.92 R2_score.

5. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

