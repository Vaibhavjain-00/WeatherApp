# 🌦️ Weather App

A simple web application that fetches real-time weather data for any city using the OpenWeatherMap API.

## 🚀 Features

* Search weather by city name
* Displays temperature and weather condition
* Error handling for invalid city names
* Clean dark-themed UI
* Responsive centered layout

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript
* OpenWeatherMap API

## 📂 Project Structure

```
weather-app/
│── index.html
│── styles.css
│── script.js
```

## ⚙️ How It Works

1. User enters a city name.
2. The app sends a request to the OpenWeatherMap API.
3. Weather data is fetched and displayed on the page.
4. If the city is not found, an error message is shown.

The app uses `fetch()` to retrieve weather data from:

```
https://api.openweathermap.org/data/2.5/weather
```

## ▶️ How to Run the Project

1. Download or clone the repository
2. Open `index.html` in your browser
3. Enter a city name and click **Get Weather**

## 🔑 API Configuration

This project uses an API key from OpenWeatherMap.

To use your own key:

1. Create an account at [https://openweathermap.org/](https://openweathermap.org/)
2. Generate an API key
3. Replace the value of `API_KEY` in `script.js`

## 📸 Output Example

Displays:

* City name
* Temperature in Celsius
* Weather description

## 🎯 Learning Purpose

This project was built to practice:

* Working with APIs
* Asynchronous JavaScript (async/await)
* DOM manipulation
* Error handling in web applications

---
