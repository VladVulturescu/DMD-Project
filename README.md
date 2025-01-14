# Weather App V7
Weather App V7 is an Android application that provides real-time weather information for any city in the world. Using the OpenWeatherMap API, users can view temperature, humidity, wind speed, and dynamic weather icons, all displayed in a user-friendly interface.

# Features
•	Fetches real-time weather data using the OpenWeatherMap API.
•	Displays:
o	Current temperature in Celsius.
o	Humidity percentage.
o	Wind speed in km/h.
o	Weather description (e.g., sunny, clear sky, etc.).
o	Dynamic icons matching the weather conditions.
•	Allows users to search for weather in any city.
•	Includes a default city (Bucharest) when the app launches.

# Technologies Used
•	Programming Language: Java
•	Framework: Android SDK
•	IDE: Android Studio
•	Dependencies:
o	OkHttp for API calls.

# Setup Instructions
1.	Clone the repository or download the project as a ZIP file.
2. 	Open the project in Android Studio.
3.	Add your OpenWeatherMap API key:
o	Open MainActivity.java.
o	Replace the API_KEY variable with your API key:
private static final String API_KEY = "API_Key";  
4.	Run the app on an emulator or physical device.

# How to Use
1.	Launch the app.
2.	By default, the weather for Bucharest is displayed.
3.	Enter the name of another city in the text field.
4.	Tap the "Change City" button to view updated weather data.
5.	The text field clears automatically after fetching data for easier input.

# Known Limitations
•	The app currently incorporates 50-60% of the required Android components (e.g., missing certain background services, notifications, or shared preferences).
•	Limited error handling for invalid city names or network issues.

# Contributors
•	Vlad (Developer)

# License
This project is for educational purposes and is not intended for commercial use.

# GitHub
https://github.com/VladVulturescu/DMD-Project
