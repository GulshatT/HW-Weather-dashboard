# HW-Weather-dashboard
https://gulshatt.github.io/HW-Weather-dashboard/

A weather dashboard that allows the user to search for the current and five day forecast of their searched city. Utilizes OpenWeather API to retrieve weather data for cities and incorporates localStorage to store data.

I Used the https://home.openweathermap.org/api_keys to retrieve weather data for cities. I used local storage to save persistent data.

User Story
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
Acceptance Criteria
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
