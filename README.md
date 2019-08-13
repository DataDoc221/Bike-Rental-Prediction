# Bike-Rental-Prediction
Developing model to predict daily bike rental count in given environmental conditions.

# Problem Statement
The objective of this Case is to Predict of bike rental count on daily basis for managing the assets for the company and improve their services.

# Introduction
Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.

# Data
instant: Record index  
dteday: Date  
season: Season (1:springer, 2:summer, 3:fall, 4:winter)  
yr: Year (0: 2011, 1:2012)  
mnth: Month (1 to 12) hr: Hour (0 to 23)  
holiday: weather day is holiday or not (extracted fromHoliday Schedule)  
weekday: Day of the week  
workingday: If day is neither weekend nor holiday is 1, otherwise is 0  
weathersit: (extracted fromFreemeteo)  
1: Clear, Few clouds, Partly cloudy, Partly cloudy  
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist  
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds  
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog  
temp: Normalized temperature in Celsius  
The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)  
atemp: Normalized feeling temperature in Celsius  
The values are derived via (t-t_min)/(t_max- t_min), t_min=-16, t_max=+50 (only in hourly scale)  
hum: Normalized humidity  
The values are divided to 100 (max)  
windspeed: Normalized wind speed. The values are divided to 67 (max) casual: count of casual users  
