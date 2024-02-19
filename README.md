This is a PyPI package "dopplerweather".
Provides a weather forecast of next 12 hours.
Arguments needed are:
1. openweathermap apikey of user.
2. either a city name or both a latitude and a longitude.

Package usage example:
Create a weather object using a city name:
The api key below is not guaranteed to work.
Get your own apikey from https://openweathermap.org/
And wait a couple of hours for the apikey to be activated.

Using city name
>>> weather1 = Weather(apikey = "4b0286c52ef756c37eb4cc5a9a28e842", city = "Pune")

Using latitude and longitude co-ordinates
>>> weather2 = Weather(apikey = "4b0286c52ef756c37eb4cc5a9a28e842", lat = 41.0, lon = -4.1)

Get complete weather data for the next 12 hours:
>>> weather1.next_12h()

Get simplified weather data for the next 12 hours:
>>> weather1.next_12h_simplified()

Sample url to get sky condition icons:
https://openweathermap.org/img/wn/10d@2x.png
