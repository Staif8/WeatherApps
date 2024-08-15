## WeatherApps


This is the README file for a Java-based weather application enables users to look for weather info in a selected location.

# Features:

* Fetches weather data from OpenWeatherMap API.
* Displays current weather situation (temperature, humidity, wind speed, and description).
* provides unit conversion between Celsius and Fahrenheit.
* Displays a weather icon based on the current conditions.
* Displays an 8-day forecast (placeholder for now).
* Maintaining a search history for previously searched locations.
* Changes the application background color based on the weather condition.

# Requirements:

Java Runtime Environment (JRE)

# Running the application:

1. Compile the Java source code using a Java compiler (e.g., javac).
2. Run the main class `Main.java`.

# Understanding the Code:

* `Main.java`: This is the entry point for the application. It creates an instance of `WeatherAppGUI` and calls its `launchApp` method to start the application.
* `UnitConverter.java`: This class provides methods for unit conversion between Celsius and Fahrenheit for temperature and kilometers per hour (km/h) to miles per hour (mph) for wind speed.
* `WeatherAPI.java`: This class handles communication with the OpenWeatherMap API to fetch weather data for a given location.
* `WeatherAppGUI.java`: This class creates the graphical user interface (GUI) for the application. It includes elements like a text field for location input, labels for displaying weather information, a combo box for unit selection, and a text area for showing the forecast. It also manages user interaction and updates the UI based on the fetched data.
* `WeatherData.java`: This class represents a weather data object, storing information like temperature, humidity, wind speed, and weather condition.
* `WeatherHistory.java`: This class maintains a history of past searches and allows retrieving weather data for previously searched locations.
* `WeatherIconManager.java`: This class manages fetching weather icons from the OpenWeatherMap website and displaying them in the GUI.


