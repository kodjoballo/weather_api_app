# 🌦️ Weather App (PyQt5 + OpenWeather API)

A desktop weather application built with **PyQt5** that fetches live weather data from the [OpenWeather API](https://openweathermap.org/api).  
Users can enter a city name and instantly see temperature, description, and weather emojis.

---

## 🚀 Features
- Modern **PyQt5 GUI**.
- Fetches real-time weather data.
- Displays:
  - 🌡️ Temperature (°C)
  - 🌥️ Weather description
  - 🌈 Emoji representing conditions
- Error handling for:
  - Invalid city names
  - Invalid API keys
  - Server issues (403, 404, 500, etc.)

---

## 🛠️ Installation

1. Clone this repository:

Optional

   ```js
   git clone https://github.com/YOUR_USERNAME/weather-app-pyqt5.git
   cd weather-app-pyqt5
   ```
## Install dependencies:

 ```js
pip install -r requirements.txt
 ```

### 📄 requirements.txt

```js
requests
PyQt5
```


### Add your OpenWeather API key in weather_app.py:


```js
api_key = "YOUR_API_KEY_HERE"
```


👉 Get a free key here: https://openweathermap.org/api


## ▶️ Usage

Run the app:

```js
python.exe weather_app.py
```


You will see a window like this:

```js

----------------------------------------------------
              Weather App
----------------------------------------------------
Enter city name:  London
Temperature: 14°C
Condition:    light rain 🌧️

```

## Demo



https://github.com/user-attachments/assets/86827d24-756e-4cf9-8f95-ac1849bc3b93



## 📦 Dependencies

requests
 – HTTP requests

PyQt5
 – GUI framework

## ⚠️ Note

Requires internet connection to fetch weather data.

Make sure to use a valid OpenWeather API key.



