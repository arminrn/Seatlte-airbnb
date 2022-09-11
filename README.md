# Seattle Airbnb data analysis
# Description

This project is the first project of Data Scientist Nanodegree on Udacity using Seattle Airbnb Open Data by following the CRISP-DM process; therefore, five steps have been implemented to analyse the data:

1- Business Understanding 
2- Data Understanding
3- Data Preparation
4- Data Modeling
5- Result Evaluation

This project aims to answer three questions which can be helpful for both guests and landlords:

1- What factors are most related to the prices of Airbnb houses?

2- What factors are most related to reviews values?

3- How can we predict the price of Seattle Airbnbs?


# Files

This repository contains four files:
1- Readme file, which contains a short description of the project and a summary of the results.
2- Listings.csv file, which is the Seattle Airbnb Open Data provided by Kaggle.
3-Seattle Airbnb price & review .ipynb, which contains the Python source code of related factors to price and review values.
4- Seattle Airbnb Price Prediction .ipynb, which contains the Python sourse code of price prediction.

# Results

Based on the seaborn heatmap, features such as bedroom, bathroom, beds, and accommodates are the most related features to price.

Based on seaborn heatmap features such as number_of_reviews, review_scores_rating, review_scores_accuracy, review_scores_cleanliness, review_scores_checkin, review_scores_communication, and review_scores_location are most related features to review score value.

Also, box plot figures have shown how categorical features like room_type, property_type, and neighbourhood_group_cleansed have a correlation with price and review score values.

Two algorithms have been used to predict the price, Linear Regression and Random Forest Regressor, and two methods have been used to evaluate the models, r2_score and mean_squared_error, and the results show:

Linear Regression: r2_score= 0.46, mean_squared_error= 4225.5

Random Forest Regressor: r2_score= 0.48, mean_squared_error= 4097.3






