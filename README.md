# Python API Challenge

In this challenge, we focused on using APIs to get data and then use it to perform further analysis and mapping. In the first part of the exercise, we focused on analysis whereas in the second part of the exercise, we focused on mapping.

## Part 1: WeatherPy

In this part, we select a random set of cities, and use OpenWeather API to get weather data for those cities. We then proceed to clean up this data and then analyze the relationship between Latitude for these cities, and their weather, namely Max Temperature, Humidity, Cloudiness and Max Wind Speed.

## Part 2: VacationPy

In this part, we use the cities data we got from Part 1 and then plot these cities on a world map, with marker size based on humidity. We used GeoView to do this. 

Then, we select some cities based on weather conditions, which are user-defined. The conditions used for this session were:
1. Max Temperature is between 18 and 25 degrees Celsius.
2. Max Wind Speed is less than 5 m/s.
3. Humidity is less than 60%.

Then we use GeoApify data to find a hotel in these cities based on coordinates from OpenWeather Data. And finally, we plot these cities, along with the hotels we found, on a world map.