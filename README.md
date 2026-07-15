# weatherprediction
# Weather Forecast Web Application

A responsive weather forecasting web application that provides real-time weather information and temperature updates for any city. The application offers a clean and intuitive interface where users can search for locations and instantly view current weather conditions using live weather data from a weather API.

---

## Features

- Search weather information by city name
- Display current temperature
- Show weather conditions (Clear, Clouds, Rain, etc.)
- Display humidity and wind speed
- Responsive user interface for desktop and mobile devices
- Real-time weather data using API integration
- Fast and user-friendly design
- Error handling for invalid city names

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Styling and Responsive Design |
| JavaScript (ES6) | Application Logic |
| Weather API | Real-Time Weather Data |

---

## Project Structure

```text
weather-forecast/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

---

## How It Works

1. The user enters a city name in the search box.
2. JavaScript sends a request to the weather API.
3. The API returns the latest weather information.
4. The application processes the response.
5. Weather details are displayed on the webpage instantly.

---

## Application Features

The application displays:

- Current Temperature
- Weather Description
- Humidity
- Wind Speed
- Weather Icon
- City Name

---

## API Integration

The application fetches live weather data through a weather API using asynchronous JavaScript (`fetch()`).

Example API request:

```http
GET https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY
```

---

## Running the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/weather-forecast.git

cd weather-forecast
```

### Run Locally

Simply open the `index.html` file in your browser.

Or use the VS Code Live Server extension.

---

## Workflow

```text
User
   │
   ▼
Enter City Name
   │
   ▼
JavaScript Fetch API
   │
   ▼
Weather API
   │
   ▼
JSON Response
   │
   ▼
Display Weather Information
```

---

## Key Highlights

- Clean and responsive user interface
- Real-time weather information
- API integration using JavaScript Fetch API
- Lightweight and fast application
- Mobile-friendly design
- Simple and maintainable project structure

---

## Future Enhancements

- 5-Day Weather Forecast
- Hourly Forecast
- Current Location Weather using Geolocation
- Air Quality Index (AQI)
- Sunrise and Sunset Information
- Weather Maps
- Dark and Light Theme
- Search History
- Favorite Cities
- Multi-language Support

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License.

---

## Author

**Shivam Mittal**

AI & Machine Learning Engineer

If you found this project useful, consider giving it a star on GitHub.
