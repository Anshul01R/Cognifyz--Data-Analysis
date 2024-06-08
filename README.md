#Cognifyz--Data-Analysis
#Level 1

Task 1: Data Exploration and Preprocessing

         -Examined a dataset containing 9,561 rows and 21 columns.

         -Managed missing values to ensure clean data for analysis.

         -Analyzed the distribution of "Aggregate Rating," with no need for data   type conversion or class balancing.



Task 2: Descriptive Analysis

         -Calculated key statistical measures for numerical data.

         -Investigated the distribution of variables such as "Country Code," "City," and "Cuisines."

         -Identified the top cuisines and cities with the highest number of restaurants.



Task 3: Geospatial Analysis

         -Visualized restaurant locations on a map using latitude and longitude.

         -Analyzed the distribution of restaurants across various cities and countries.

         -Investigated correlations between restaurant locations and their ratings.
         
#Level 2

Table Booking & Online Delivery

         Availability: 12.12% of restaurants offer table booking, while 25.66% provide online delivery.
         
         Average Ratings: Restaurants with table booking have an average rating of 3.44, compared to 2.56 for those without.

Price Range Analysis

         Commonality: The most frequent price range is 1.
         
         Top Ratings: The highest average rating, 3.82, is found in price range 4.
         
Feature Engineering

         New Features: I extracted new features such as the length of the restaurant name and address.
         
         Encoded Features: I encoded new features like "Has Table Booking" and "Has Online Delivery."
         
Key Insights

         Service Impact
         
                  Restaurants offering table booking services achieve significantly higher ratings.
                  
         Online Delivery
         
                  Online delivery services are most common in mid-range price categories.
                  
         High-End Focus
         
                  Despite being fewer in number, restaurants in price range 4 receive the highest average ratings.
                  
Recommendations

         Expand table booking and online delivery services to boost customer satisfaction.
         
         Focus marketing on mid-range price categories where online delivery is more common.
         
         Promote high-end dining experiences, leveraging the high ratings in price range 4.

#LEVEL 3

Task 1:- Predictive Modeling
Task 2:- Customer Preference Analysis
Task 3:- Data Visualization
Here's a glimpse of what I accomplished:-

◉ Data Visualization:

         > Distribution of Ratings: Visualized using histograms and bar plots to understand the spread and central tendency of restaurant ratings.
         > Cuisine and City Comparison: Bar charts and box plots were used to compare average ratings across different cuisines and cities, providing a clear picture of regional and culinary preferences.
         > Feature Relationships: Scatter plots and correlation matrices helped visualize the relationships between various features and the target variable, offering deeper insights into the factors influencing          restaurant ratings.

◉ Key Observations:

         Linear Regression:-
         
                  > Mean Squared Error (MSE): 1.5085
                  
                  > R-squared: 0.8284
                  
                  > Observation : While Linear Regression provided a decent fit, it showed the highest MSE among the models, indicating lower accuracy in predicting restaurant ratings.

         Decision Tree::-
                  > MSE: 0.7872
                  
                  > R-squared: 0.9198
                  
                  > Observation : The Decision Tree model significantly improved prediction accuracy over Linear Regression, with a substantial reduction in MSE and a higher R-squared value.

         Random Forest:-
         
                  > MSE: 0.2137
                  
                  > R-squared: 0.9433
                  
                  > Observation: The Random Forest model outperformed both Linear Regression and Decision Tree models. It achieved the lowest MSE and the highest R-squared value, making it the most accurate                          model in our study.


◉ Recommendations:-

         • Adopt Advanced Models: For businesses looking to predict customer ratings accurately, advanced models like Random Forest should be preferred due to their higher accuracy and robustness.
         
         • Focus on Popular Cuisines: Restaurants can leverage insights on popular cuisines to tailor their menus and marketing strategies, aligning more closely with customer preferences.
         
         • Continuous Analysis: Regularly updating and analyzing the model with new data can help maintain high accuracy and relevance, adapting to changing customer tastes and trends.

