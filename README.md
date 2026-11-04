# 🌦️ WeatherXp

A clean, responsive web app that gives you real-time weather information and a multi-day forecast for your location. Allow location access and WeatherXp fetches live weather data from the OpenWeatherMap API and displays it instantly.

🔗 **Live Demo:** [https://ayush05102001.github.io/WeatherXp/](https://ayush05102001.github.io/WeatherXp/)

---

## ✨ Features

- **Location-based weather** – detects your current location using the browser's Geolocation API
- **Real-time data** – live weather information fetched from the OpenWeatherMap API
- **Live clock and date** – shows the current time, day, and date
- **Time zone and country** – displays your time zone and country code
- **Multi-day forecast** – upcoming days with separate day and night temperatures
- **Dynamic weather icons** – icons change to match the forecast conditions
- **Responsive design** – works smoothly on desktop, tablet, and mobile

---

## 🌡️ Weather Information Displayed

| Data                 | Description                                  |
|----------------------|----------------------------------------------|
| 🕒 Time & Date       | Current local time, day, and date            |
| 🌍 Time Zone         | Your detected time zone                      |
| 📍 Country           | Country code for your location               |
| ☀️ Day Temperature   | Daytime temperature for each forecast day    |
| 🌙 Night Temperature | Nighttime temperature for each forecast day  |
| ☁️ Weather Icon      | Visual icon for the expected conditions      |

---

## 🛠️ Tech Stack

- **HTML5** – structure and layout
- **CSS3** – styling, responsive design, and animations
- **JavaScript (ES6+)** – API requests, geolocation, and DOM updates
- **OpenWeatherMap API** – source of live weather and forecast data
- **Geolocation API** – detects the user's current coordinates

---

## ⚙️ How It Works

1. The user opens the app and allows location access.
2. JavaScript uses the browser's **Geolocation API** to get the user's latitude and longitude.
3. The coordinates are sent to the **OpenWeatherMap API** using `fetch()`.
4. The API responds with weather and forecast data in JSON format.
5. JavaScript parses the response and updates the page with the current weather and forecast.

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- A free API key from OpenWeatherMap
- Git (optional, for cloning)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ayush05102001/WeatherXp.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd WeatherXp
   ```

3. **Add your API key**

   Open `script.js` and replace the placeholder with your own key:
   ```javascript
   const API_KEY = "your_api_key_here";
   ```

4. **Run the app**

   Open `index.html` in your browser, or serve it locally:
   ```bash
   python -m http.server 8000
   ```

   > **Note:** Most browsers only allow geolocation on `localhost` or HTTPS, so running a local server is recommended.

---

## 🎮 How to Use

1. Open WeatherXp in your browser, or visit the live demo.
2. Click **Allow** when the browser asks for your location.
3. View the current time, your location details, and the weather forecast for your area.

---

## 📁 Project Structure

```
WeatherXp/
├── index.html          # Main page
├── style.css           # Styles and layout
├── script.js           # API calls, geolocation, and UI logic
└── README.md
```

---

## 🔒 Privacy

WeatherXp only uses your location to fetch weather data for your area. Your location is not stored or shared anywhere.

---

## 🔮 Future Improvements

- [ ] City search to check weather anywhere
- [ ] Hourly forecast
- [ ] Toggle between Celsius and Fahrenheit
- [ ] Dark / light mode
- [ ] Background that changes with weather conditions
- [ ] Air quality index (AQI)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/city-search`)
3. Commit your changes (`git commit -m "Add city search"`)
4. Push to the branch (`git push origin feature/city-search`)
5. Open a Pull Request

---