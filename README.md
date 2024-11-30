# Weather App 🌤️

A simple weather application built using HTML, CSS, and JavaScript. It fetches real-time weather data using the OpenWeatherMap API and displays it to the user. 

## Features
- **Search by City:** Enter the name of a city to get its current weather.
- **Real-Time Data:** Fetches live data including temperature, humidity, and wind speed.
- **Dynamic Weather Icons:** Displays appropriate icons based on the weather condition (e.g., clouds, clear sky, rain).
- **Error Handling:** Shows an error message for invalid city names.

---

## Installation and Usage

### Prerequisites
1. An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Setup
1. Clone the repository or download the project files.
2. Open the `index.html` file in any web browser.
3. Ensure your project structure contains the following:
   - `index.html` for the UI
   - `style.css` for styling
   - `script.js` for functionality
   - `images/` folder containing weather icons (`clouds.png`, `clear.png`, `rain.png`, `drizzle.png`, `mist.png`).

### How to Use
1. Open the app in your browser.
2. Enter a city name in the search bar.
3. Click the "Search" button to view the weather details.
4. The weather information will display below the search bar or an error message if the city is not found.

---

## Project Structure

```
weather-app/
│
├── index.html        # Main HTML file
├── style.css         # Styling for the app
├── script.js         # JavaScript for functionality
├── images/           # Folder containing weather icons
│   ├── clouds.png
│   ├── clear.png
│   ├── rain.png
│   ├── drizzle.png
│   ├── mist.png
```

---

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Styling for the user interface.
- **JavaScript**: Adds interactivity and fetches data from the API.

---

## API Reference
This app uses the **OpenWeatherMap API** to fetch weather data.  
API Endpoint:  
```
https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={your_api_key}
```

Replace `{city}` with the city name and `{your_api_key}` with your OpenWeatherMap API key.

## Future Enhancements
- Add more weather details like sunrise/sunset times.
- Enable searching using the current location.
- Include a forecast feature for the next few days.

---
### Author
Feel free to reach out for collaboration or questions! 😊
