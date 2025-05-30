# 🌦️ Simple Weather App

A minimalist weather application built using **HTML**, **CSS**, and **JavaScript**, which fetches real-time weather data using the **OpenWeatherMap API**. Users can enter a city name to get the current weather, including temperature and conditions.

---

## 📸 Preview

![Weather App Screenshot]<img width="959" alt="image" src="https://github.com/user-attachments/assets/d622d86d-f663-4ee2-8792-75250a45bd0a" />


---

## 🔧 Features

- 🔍 Search weather by **city name**
- 🌍 Uses **Geocoding API** to convert city names into coordinates
- 📡 Fetches weather data in **real-time**
- 🌤️ Displays:
  - City name
  - Temperature in Celsius
  - Weather description
  - Weather icon
- ❌ Handles:
  - Empty input
  - Invalid city names
  - Failed API requests

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6+)**
- **[OpenWeatherMap API](https://openweathermap.org/api)**

---

## 📂 Project Structure

```

/weather-app
│
├── index.html           # Main HTML file
├── weather.js           # JavaScript for fetching & displaying weather
├── style.css            # Basic styling

````

---

## ⚙️ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Get your API key** from [OpenWeatherMap](https://openweathermap.org/api) and replace the placeholder in `weather.js`:

   ```javascript
   const apiKey = "your_api_key_here";
   ```

3. **Open** the `index.html` file in your browser.

---

## 🧠 How It Works

* User enters a **city name**.
* The app uses **OpenWeatherMap’s Geocoding API** to get latitude and longitude.
* Those coordinates are used in a **weather data API request**.
* The response is parsed and displayed on the UI.

---

## 🧪 Error Handling

The app will show user-friendly messages for:

* Empty inputs
* Non-existent cities
* API or network failures

---

## 🙌 Contributing

Contributions are welcome! Feel free to:

* Report bugs
* Suggest features
* Open pull requests

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Credits

* Icons and data from [OpenWeatherMap](https://openweathermap.org/)
* UI design inspiration from clean and minimal weather apps
* Project inspired by Codedex's "View Weather with HTML, CSS & JS"
---

## 📬 Contact

Created by [Shaun](https://github.com/Pxdarkshadow) – feel free to connect!

````
