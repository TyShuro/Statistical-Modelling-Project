# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Explore Data from API's and build a statistical model
Data Collection: Gather relevant data from various sources to build a comprehensive dataset.
Statistical Modelling: Apply statistical models to analyze the data 
## Process
Part 1: Data Collection

Identify Data Sources:

Determine the primary data sources for the project, including Foursquare and Yelp.

Access API Documentation:

Review the API documentation of Foursquare and Yelp to understand data retrieval methods and endpoints.

API Requests:

Make API requests to Foursquare and Yelp to gather relevant data, such as business details, user reviews, and location information.

Data Cleaning:

Clean and preprocess the collected data to ensure accuracy and consistency.

### (your step 2)

## Results
The selected area had a significant difference in terms of the number of points of interest (POIs) found between API providers. By comparison, Foursquare offered a well-distributed variety of POI categories throughout the entire region. However, Yelp had more POIs in commercial districts and less in residential areas.

A regression model predicting the number of bikes available at various stations based on POI characteristics yielded limited explanatory power with an R-squared value of only 0.014. This shows that the current variables present very little information about what affects the number of available bikes; as such, this model does not have much to offer. Despite some predictors being statistically significant, overall model fit was poor and residuals not normally distributed signifying either model assumptions violations or need for inclusion of more explanatory variables

## Challenges 
Data Integration: Combining data from diverse sources and formats posed challenges in terms of data cleaning and integration.

Data Quality: Ensuring the accuracy and reliability of the collected data was a continuous effort. Cleaning noisy data was a time-consuming task.

## Future Goals
If given more time, I would implement the following - 
Geospatial Analysis: Use geospatial analysis to understand the spatial relationships and patterns that may affect bike station popularity and, consequently, bike availability.

User Behavior Analysis: Study user behavior through surveys or app data to understand the motivations behind bike rentals, which could provide insights for feature selection.

Real-Time Analytics: Develop a system for real-time prediction of bike availability to aid in dynamic allocation and redistribution of bikes.
