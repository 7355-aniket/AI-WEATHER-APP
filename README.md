# 🌦️ Weather App Using Python

A simple and interactive **Weather Application built with Python** that fetches real-time weather information for any city using the **Open-Meteo REST API**. The application provides temperature, humidity, wind speed, precipitation, and weather conditions through an interactive Google Colab interface.

---

## 🚀 Project Overview

The Weather App allows users to enter the name of a city and retrieve its current weather information.

The application first uses a **Geocoding API** to convert the city name into latitude and longitude coordinates. It then uses the **Weather API** to retrieve the current weather data and displays the results in an easy-to-understand weather card.

### ✨ Key Features

* 🔍 Search weather by city name
* 🌡️ Current temperature
* 🌡️ Feels-like temperature
* ☁️ Current weather condition
* 💧 Humidity percentage
* 💨 Wind speed
* 🌧️ Precipitation
* 📍 City and country information
* ⚠️ Error handling for invalid cities
* 🖥️ Interactive GUI using IPyWidgets
* 🌐 Real-time data through REST APIs
* 🔑 No API key required

---

## 🛠️ Technologies Used

| Technology   | Purpose                      |
| ------------ | ---------------------------- |
| Python       | Main programming language    |
| Requests     | API requests                 |
| REST API     | Fetching weather information |
| JSON         | Processing API responses     |
| IPyWidgets   | Interactive user interface   |
| HTML/CSS     | Weather card design          |
| Google Colab | Development environment      |
| Open-Meteo   | Weather and geocoding data   |

---

## 🧠 How It Works

```text
              USER
                │
                ▼
        Enter City Name
                │
                ▼
        Geocoding API
                │
                ▼
       Latitude + Longitude
                │
                ▼
         Weather API
                │
                ▼
          JSON Response
                │
                ▼
```
