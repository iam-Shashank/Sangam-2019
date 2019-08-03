# Sangam-2019


Observations: 

- dew_point is highly correlated with visibility_in_miles (ρ = 1). So, one column rejected?

- Maximum days no rain or snow.( as there are lots of zeroes)

- Most days are cloudy, windy (as no. of zeroes is low)

- Temperature value has one 0 Kelvin value 



Categorical: Date-Time, weather_description, weather_type, is_holiday

Date-Time: split into Date and Time



Weather_type:

'Clouds',
'Clear' ,
'Rain',
Drizzle',
'Mist',
'Haze',
'Fog',
'Thunderstorm',
Snow',
'Squall',
'Smoke


weather_description:
['scattered clouds',
 'broken clouds',
 'overcast clouds',
 'sky is clear',
 'few clouds',
 'light rain',
 'light intensity drizzle',
 'mist',
 'haze',
 'fog',
 'proximity shower rain',
 'drizzle',
 'moderate rain',
 'heavy intensity rain',
 'proximity thunderstorm',
 'thunderstorm with light rain',
 'proximity thunderstorm with rain',
 'heavy snow',
 'heavy intensity drizzle',
 'snow',
 'thunderstorm with heavy rain',
 'freezing rain',
 'shower snow',
 'light rain and snow',
 'light intensity shower rain',
 'SQUALLS',
 'thunderstorm with rain',
 'proximity thunderstorm with drizzle',
 'thunderstorm',
 'Sky is Clear',
 'very heavy rain',
 'thunderstorm with light drizzle',
 'light snow',
 'thunderstorm with drizzle',
 'smoke',
 'shower drizzle',
 'light shower snow',
 'sleet'
