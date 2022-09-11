# Seattle airbnb data analysis
#Description

This project is the first projetc of Data Scientist Nanodegree on Udacity using Seattle Airbnb Open Data by following the CRISP-DM process, therefore 5 steps have implemented to analyse the data:

1- Business Understanding 
2- Data Understanding
3- Data Preparation
4- Data Modeling
5- Result Evaluation

This project aims to answer to 3 questions which can be helpful for both guests and landlords:
1- What factors are most related to the prices of airbnb houses?
2- What factors are most related to reviews values?
3- How we can predict the price of Seattle Airbnbs?

#Files

This repository contains 4 files:
1- Readme file which contains a small description of the project and the summary of the results.
2- Listing.csv file, which is the Seattle Airbnb Open Data provided by kaggle.
3-Seattle airbnb price & review .ipynb, which contains the Python sourse code of related factors to price and review values.
4- Seattle airbnb Price Prediction .ipynb, which contains the Python sourse code of price prediction.

#Results

Based on seaborn heatmap features such as bedroom, bathroom, beds, and accomodates are the most related features to price.
Based on seaborn heatmap features such as number_of_reviews, review_scores_rating, review_scores_accuracy, review_scores_cleanliness, review_scores_checkin, review_scores_communication, and review_scores_location are most related features to review score value.
Also, box plot figues have shown how cathegorical features like, room_type, property_type, and neighbourhood_group_cleansed have correlation with price and review score values.

Two algorythms have been used to predict the price, Linear Regression and Random Forest Regressor, and two method have been used to evaluate the models, r2_score, and mean_squared_error and the results shows:
Linear Regression: r2_score= 0.46, mean_squared_error= 4225.5
Random Forest Regressor: r2_score= 0.48, mean_squared_error= 4097.3






