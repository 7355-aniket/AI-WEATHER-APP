# 🌦️ Weather App Using Python

A simple and interactive **Weather Application built with Python** that fetches real-time weather information for any city using the **Open-Meteo REST API**. The application provides temperature, humidity, wind speed, precipitation, and weather conditions through an interactive Google Colab interface.

---

## 🚀 Project Overview

The Weather App allows users to enter the name of a city and retrieve its current weather information.

The application first uses a **Geocoding API** to convert the city name into latitude and longitude coordinates. It then uses the **Weather API** to retrieve current weather data and displays the results in an easy-to-understand weather card.

---

## ✨ Key Features

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
* 🌐 Real-time weather data
* 🔑 No API key required

---

## 🛠️ Technologies Used

| Technology   | Purpose                      |
| ------------ | ---------------------------- |
| Python       | Main programming language    |
| Requests     | Sending API requests         |
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
          Python Data Processing
                   │
                   ▼
         Interactive Weather Card
```

---

## 📂 Project Structure

```text
Weather-App/
│
├── Weather_App.ipynb
├── README.md
├── requirements.txt
└── screenshots/
    └── weather-app.png
```

---

## ⚙️ Installation

### 1. Open Google Colab

Open the project notebook in Google Colab.

### 2. Install Required Libraries

Run:

```python
!pip install requests ipywidgets
```

---

## ▶️ How to Run

1. Open the `Weather_App.ipynb` notebook.
2. Run the installation cell.
3. Run the main application cell.
4. Enter a city name in the input box.
5. Click **Get Weather**.
6. View the current weather information.

### Example Input

```text
Pune
```

### Example Output

```text
🌦️ Weather Information

📍 Pune, India

🌡️ Temperature: 27°C
☁️ Condition: Partly Cloudy
💧 Humidity: 72%
💨 Wind Speed: 12 km/h
🌧️ Precipitation: 0 mm
```

> The displayed values depend on the live weather data returned by the API.

---

## 🌐 API Used

This project uses **Open-Meteo** to obtain weather and geocoding information.

### Geocoding API

```text
https://geocoding-api.open-meteo.com/v1/search
```

The Geocoding API converts a city name into geographic coordinates.

### Weather API

```text
https://api.open-meteo.com/v1/forecast
```

The Weather API retrieves current weather information using latitude and longitude.

---

## 📊 Weather Information

The application displays several weather parameters.

### 🌡️ Temperature

Shows the current temperature of the selected location.

### 🌡️ Feels Like

Shows the apparent temperature experienced at the selected location.

### 💧 Humidity

Displays the relative humidity percentage.

### 💨 Wind Speed

Displays the current wind speed in km/h.

### 🌧️ Precipitation

Displays the current precipitation measurement.

### ☁️ Weather Condition

Weather codes returned by the API are converted into readable descriptions such as:

```text
☀️ Clear Sky
🌤️ Mainly Clear
⛅ Partly Cloudy
☁️ Overcast
🌧️ Rain
⛈️ Thunderstorm
```

---

## 🧩 Python Concepts Used

This project demonstrates several important Python concepts:

* Variables
* Functions
* Dictionaries
* Conditional statements
* Exception handling
* API requests
* JSON parsing
* String formatting
* GUI widgets
* HTML generation
* Error handling

---

## 🔄 API Data Flow

```text
City Name
    ↓
Geocoding API
    ↓
Latitude & Longitude
    ↓
Weather API
    ↓
JSON Data
    ↓
Python Processing
    ↓
Weather Information
    ↓
GUI Display
```

---

## ⚠️ Error Handling

The application handles common errors such as:

* Empty city name
* Invalid city name
* City not found
* API connection problems
* Unexpected errors

Example:

```text
❌ City not found. Please try again.
```

---

## 🔮 Future Improvements

The application can be enhanced with additional features:

* 📅 7-day weather forecast
* 🌅 Sunrise and sunset times
* 🌙 Day/night weather themes
* 📍 Automatic location detection
* 🗺️ Interactive maps
* 📊 Temperature graphs
* 🌧️ Rain probability
* 💨 Wind direction
* 🌡️ Celsius/Fahrenheit conversion
* 📱 Mobile-friendly interface
* 🔔 Weather alerts
* 🌍 Multiple-city comparison

---

## 🎯 Learning Objectives

By completing this project, you can learn how to:

1. Build a Python-based application.
2. Work with REST APIs.
3. Send HTTP requests using Python.
4. Process JSON responses.
5. Work with geographic coordinates.
6. Create an interactive interface.
7. Handle API errors.
8. Display dynamic data using Python and HTML.

---

## 📸 Project Preview

Add a screenshot of the application to the `screenshots` folder.

Then use:

```markdown
![Weather App Screenshot](screenshots/weather-app.png)
```

Recommended structure:

```text
Weather-App/
│
├── screenshots/
│   └── weather-app.png
│
├── Weather_App.ipynb
├── README.md
└── requirements.txt
```

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
requests
ipywidgets
```

Install the requirements using:

```bash
pip install -r requirements.txt
```

---

## 💻 Example

### Input

```text
Mumbai
```

### Output

```text
🌦️ Weather Information

📍 Mumbai, India

🌡️ Temperature: 29°C
☁️ Condition: Partly Cloudy
🌡️ Feels Like: 31°C
💧 Humidity: 75%
💨 Wind Speed: 14 km/h
🌧️ Precipitation: 0 mm
```

> Example values are for demonstration. The application displays live values returned by the weather API.

---

## 👨‍💻 Author

**Aniket Shukla**

---

## ⭐ Support

If you found this project useful, consider giving the project a ⭐.

---

## 📄 License

This project is created for **educational and portfolio purposes**.
