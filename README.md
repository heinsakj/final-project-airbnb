# Final project - Predicting prices for airbnb listings in Berlin
Understanding the Berlin market from a tenant and landlord perspective
1. Predicting prices for future landlords
2. Most expensive airbnb 
3. Recommend the best airbnb's and experiences in Berlin to friends/family.

## 1. Motivation
For my final project at the Ironhack Bootcamp I decided to analyse the Berlin Airbnb market. As Berlin is one of the most visited cities in Europe, Airbnb plays an important role when it comes to accommodation. As Airbnb's ecosystem also offers experiences one can plan a perfect stay in Berlin via Airbnb, which is why I wanted to do a deep dive into the airbnb ecosystem and understand various relationships.

## 2. Features
Check out my final project presentation for a quick overview or [my tableau page](https://public.tableau.com/app/profile/anna.heins/viz/airbnb-finalproject/Neighbourhoodsandprediction?publish=yes) to get some data evaluation insights.

## 3. Data
- [1] Airbnb listing data was downloaded via the following [webpage](http://insideairbnb.com/get-the-data/)
- [2] Experience data was scraped from airbnb experiences using [Selenium](https://selenium-python.readthedocs.io/) and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

### 3.1 Cleaned Data
For the analysis the following cleaned data sets were used:
1. listings_cleaned.csv
2. experience.csv

## 4. Model
The prediction model was built and optimized using hyperparameters and feature selection. Resulting in the RandomForestRegressor providing the best results in terms of RMSE.

## 5. Credits
Credits go to this notebook [kaggle book](https://www.kaggle.com/code/lennarthaupts/airbnb-prices-in-berlin/notebook)
