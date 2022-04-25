# Bike sharing demand
Forecast use of a city bikeshare system

## Goal of the project
Capital Bikeshare is a bicycle-sharing system. I would like to find out how many bicycles need to be ready at a given time in Washington DC.

Modelling project, consisting of build and train a regression model in order to predict demand based on time and weather.

## Description of the dataset
Dataset founded on Kaggle with the hourly rental data from 2011 and 2012. We already have the training set and the separate test set. 
The training set (10886 rows) consists of the first 19 days of the month, and the test set (6493 rows) from the 20th day of the month.
I would like to predict the total count of bikes rented during each hour covered by the test set.

It contains 11 features: 

· Datetime - hourly date + timestamp  

· Season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 

· Holiday - whether the day is considered a holiday

· Workingday - whether the day is neither a weekend nor holiday

· Weather - 1 = Clear,party cloudly / 2 = Mist + cloudy / 3 = Rain, snow / 4 = Heavy rain, snow+fog
    
· Temp - temperature in Celsius

· Atemp - "feels like" temperature in Celsius

· Humidity - relative humidity

· Windspeed - wind speed

· Casual - number of non-registered user rentals initiated

· Registered - number of registered user rentals initiated

· Count - number of total rentals (what we want to predict)

