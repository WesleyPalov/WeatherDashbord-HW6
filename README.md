# WeatherDashbord-HW6

Third-party APIs has been used to access data and by making requests with specific parameters to a URL. A weather dashboard has been build to run in the browser and feature dynamically updated HTML and CSS.

Used the [5 Day Weather Forecast](https://openweathermap.org/forecast5) to retrieve weather data for cities. The base URL should look like the following: `https://api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon}&appid={API key}`.

LocalStorage has been used to store any persistent data.

User Story
As a traveler
I want to see the weather outlook for multiple cities
so that I can plan a trip accordingly
Further Information
Uses the OpenWeather API to retrieve weather data for cities.

Uses AJAX to hook into the API to retrieve data in JSON format.

Runs in the browser and features dynamically updated HTML and CSS powered by jQuery.

Displays the following under current weather conditions:

City

Date

Icon image (visual representation of weather conditions)

Temperature

Humidity

Wind speed

UV index

Includes a search history so that users can access their past search terms. Clicking on the city name performs a new search that returns current and future conditions for that city.

Includes a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast displays the following:

Date

Icon image (visual representation of weather conditions)

Temperature

Humidity

Uses localStorage to bring up last searched city forecast and search history on page load).
