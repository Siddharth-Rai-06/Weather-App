
# Weather App


This project makes use of the One Call API provided by Open Weather Maps.
In this project we simply make of this APi to fetch data of the temperature by passing in the city name as query.
Currently, this app doesn't work because the API key expired.
But in future this project will be updated with better fuctionalities.



## Data Provided

- Current weather
- Minute forecast for 1 hour
- Hourly forecast for 48 hours
- Daily forecast for 8 days
- National weather alerts
- Historical weather data for 40+ years back (since January 1, 1979)




## API Call
 Use the following syntax to make the API call:
 https://api.openweathermap.org/data/3.0/onecall?lat= {lat} &lon= {lon} &exclude= {part} &appid= {API key}

 *Exclude the blank spaces.*
## Parameters

- lat, lon {latitude, longitude}: <Required> *Geographical coordinates*
- appid: <Required> *Your unique API key*
- exclude: <Optional> *Exclude the parts of the weather data from the API response you don't require*
- units: <Optional> *Units of measurement. standard, metric and imperial*
- lang: <Optional> *Specify the language for your input*
## Rederence

For extensive reference, visit https://openweathermap.org/api
