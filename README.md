# bike-share-analysis 

On this project, the aim is to predict number of total rental using machine learning (ML) algorithms. Before ML process, feature engineering and exploratory data analysis is a must to examine the data.

## Let's explore the data

- instant - number of rows
- dteday - hourly date
- season - 
  - 1 = spring, 2 = summer, 3 = fall, 4 = winter
- yr - year
- mnth -month
- hr - hour
- holiday - whether the day is considered a holiday
- weekday - week of the day
- workingday - whether the day is neither a weekend nor holiday
- weathersit - 
  - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp - temperature in Celsius
- atemp - "feels like" temperature in Celsius
- hum - relative humidity
- windspeed - wind speed
- casual - number of non-registered user rentals initiated
- registered - number of registered user rentals initiated
- cnt - number of total rentals

#### *To add-on, some statistical analysis like MA, ARIMA, SARIMA, etc also applied to compare the results. Please check the notebook for different methods.*
