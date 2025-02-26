# Weather-Web-Application

This **Weather App** is a simple web-based application that allows users to check the current weather conditions for a specific location. It fetches weather data using the **OpenWeatherMap API** and displays information such as:

- **Temperature** (in Celsius)
- **Weather condition description** (e.g., Clear, Rainy, Snowy)
- **Humidity level**
- **Wind speed**
- **Weather icons** representing the current weather condition

### **How it Works**
1. The user enters a **city name** in the search box.
2. The app fetches weather data from the **OpenWeatherMap API**.
3. If the city exists, the app displays:
   - A weather icon (sun, rain, snow, etc.)
   - The temperature in **Celsius**
   - A short weather description (e.g., "Light rain")
   - Humidity percentage
   - Wind speed in km/h
4. If the city is **not found**, a "404 - Invalid location" message is displayed.

### **Key Features**
- **User-friendly Interface:** Clean and modern UI with a search bar for entering city names.
- **Real-time Weather Data:** Fetches live weather updates using API.
- **Dynamic UI Updates:** The app changes weather icons and displays details dynamically based on API responses.
- **Error Handling:** Shows a "not found" message if an invalid location is entered.

This app is built using **HTML, CSS, and JavaScript**, making it lightweight and easy to use in web browsers.

To launch the app, simply install **Live Server** in **VS Code**. Once installed, right-click the **index.html** file and select **"Open with Live Server."** The app will then automatically open in your browser, ready to use.
