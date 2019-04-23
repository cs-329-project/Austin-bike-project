# Austin-bike-project

Project Report.pdf - The final project report, which was also turned in on Canvas.

## Data files in the data folder

bike_use.csv - Used in Membership Ride Duration with Weather.ipynb to load in specific B-Cycle data with the Checkout Date column reformatted into a DateTime type. 

austin_weather.csv - Used in Membership Ride Duration with Weather.ipynb to load in Austin weather data that is then feature engineered in the notebook. 

## Data exploration

Cleaned_Data_Exploration.ipynb - Data exploration / visualization. Shows usage per day of the week, usage by month, distribution of ride duration, distribution of checkout time. Also shows bad kiosks (and removes these from the dataset). 

Membership Breakdown.ipynb - Data exploration / visualization. Take in the raw B-Cycle data and then observe the member type breakdown and average ride duration over time. We see that the makeup of membership type changes over the years.

## Darwin models remarked upon in the final report
Predicting total number of trips.ipynb / .html - Darwin model built to predict the total number of B-Cycle rides in a day.

Predicting trip length.ipynb / .html - Darwin model built to predict the average trip length of B-Cycle rides in a day.

## A failed attempt at clustering

Member Ride Duration with Weather.ipynb - Failed attempt at associating member type and weather (rain, temp, humidity) to cluster usage and predict how users ride  

## Files in the Data folder:

Cleaned_Cycle_Trips_Weather_Data.csv - The data after we combined the trip data with weather data and removed unnecessary columns/incomplete records.

Cycle_weather_by_day.csv - The data for cycle weather after we dropped unnecessary columns.
