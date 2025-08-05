Weatherly is a Flutter-based weather application that provides real-time weather updates for cities around the world. When the app is launched, users first see a custom app icon, followed by a splash screen. After that, a help screen appears with a background design and a message that reads "We show weather for you", along with a Skip button.

The app features two main screens: the Help Screen and the Home Page. If the user does not interact, the app automatically transitions from the Help Screen to the Home Page after a short delay. Pressing the Skip button also immediately takes the user to the Home Page.

On the Home Page, the app initially displays the weather based on the user’s current location. Users can search for weather in other cities using the search bar. Once a city is entered and searched, the input clears automatically, and the weather data for that city is shown. The displayed data includes the country name, city name, temperature in °C, weather condition, humidity level, and wind speed.

If the search is attempted with an empty input, a dialog box appears prompting the user to "enter the location." In such cases, the app continues to display weather data for the current location by default.

Weatherly uses the WeatherAPI (https://www.weatherapi.com/) and relies on the http package in Flutter to fetch and display accurate weather information.