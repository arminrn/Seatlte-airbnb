# Seattle airbnb data analysis
1- Business understanding
In this part, we are going to see, based on Seattle Airbnb Open Data which is provided by kaggle (listing datase), what factors are most related to: 
a- Price
b- Review Score Value
Knowing about factors which affected to the price and review score of customers can be helpful for both hosts and landlords.    

2- Data understanding
There 3 files on dataset that only Listing dataset was useful for our evaluation. Based on Listing dataset, there are 30 columns, and 20 columns have been chosen to analyse the price and revew score value. Among these 20 columns 12 columns had missing values. 

3- Data preparation
A function has been created to replace NA with 0 in review related featueres due to the high missing values in these column, then rest of columns with minor missing values has been droped.
Finally, quantitaive features have been seperated from categorical features for further evaluation.

4- Data Modeling
Two methods have been used to evaluate the data, seaborn heatmap for evaluating quantitative features, and box plot to evaluate categorical features.

5- Result Evaluation
Based on seaborn heatmap features such as bedroom, bathroom, beds, and accomodates are the most related features to price.
Based on seaborn heatmap features such as number_of_reviews, review_scores_rating, review_scores_accuracy, review_scores_cleanliness, review_scores_checkin, review_scores_communication, and review_scores_location are most related features to review score value.
Also, box plot figues have shown how cathegorical features like, room_type, property_type, and neighbourhood_group_cleansed have correlation with price and review score values.
