# Austin-bike-project

Project Report.pdf - The final project report, which was also turned in on Canvas.

## Data files in the data folder

## Project File Breakdown

## Data exploration

__Cleaned_Data_Exploration.ipynb__ - Data exploration / visualization. Shows usage per day of the week, usage by month, distribution of ride duration, distribution of checkout time. Also shows bad kiosks (and removes these from the dataset). 

__Membership Breakdown.ipynb__ - Data exploration / visualization. Take in the raw B-Cycle data and then observe the member type breakdown and average ride duration over time. We see that the makeup of membership type changes over the years.

## Feature Engineering  

__Cleaned_Feature_Engr.ipynb__ - Created a new dataset to be fed to darwin. Combined and engineered features from both the cycle and weather datasets. 

## Darwin models remarked upon in the final report
__Predicting total number of trips.ipynb /.html__ - Darwin model built to predict the total number of B-Cycle rides in a day.

__Predicting trip length.ipynb /.html__ - Darwin model built to predict the average trip length of B-Cycle rides in a day.

## A failed attempt at clustering

__Member Ride Duration with Weather.ipynb__ - Failed attempt at associating member type and weather (rain, temp, humidity) to cluster usage and predict how users ride  

## Files in the Data folder:

__Original_Austin_B-Cycle_Trips.csv__ - This is the original cycle dataset we obtained off the internet.  
__NOTE: This dataset must be uncompressed before using with notebook.__ 

__austin_weather.csv__ - This is the original weather dataset we obtained off the internet.  


__cleaned_final_b_cycle_data.csv__ - B-Cycle data that has been cleaned and processed from all the exploration conducted in the Cleaned_Data_Exploration notebook. This dataset was used to engineer features in the cleaned_feature_engr notebook. __NOTE: This dataset must be uncompressed before using with notebook.__ 

__cleaned_austin_weather.csv__ - weather data that has been cleaned and processed from all the exploration conducted in the Cleaned_Data_Exploration notebook. This dataset was used to engineer features in the cleaned_feature_engr notebook. 


__final_cycle_weather_by_day.csv__ - The final version of the cycle and weather data that has been cleaned and engineered for darwin.

__cycle_weather_by_day_with_avgs_trimmed.csv__ -  cycle and weather data that has been trimed to exclude rows where the 'Avg Trip Duration' is longer than 60 minutes. This is generated and utilized in Predicting trip length.ipynb.

