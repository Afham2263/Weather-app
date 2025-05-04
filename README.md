
## 🌦️ Weather App — PyQt5 + OpenWeatherMap

A sleek, minimal, and emoji-powered weather application built using **Python**, **PyQt5**, and the **OpenWeatherMap API**.  
Type a city name, hit the button, and BOOM — get real-time weather data with a clean UI and cute weather emojis ☀️🌧️🌪️.

---

### 🚀 Features

✅ Simple and responsive GUI using **PyQt5**  
✅ Real-time weather updates with **OpenWeatherMap API**  
✅ Clean layout with styled widgets  
✅ Cute weather emojis based on weather condition codes  
✅ Full error handling for bad requests, invalid cities, API issues, and internet errors

---

### 🔧 How It Works

- Enter a **city name**
- Click **"Get Weather"**
- The app fetches the current temperature (in Celsius) and weather condition
- Displays the data with large font and appropriate emoji

---

### 📦 Requirements

- Python 3.x  
- PyQt5  
- `requests` module  
- A free API key from [OpenWeatherMap](https://openweathermap.org/)

Install dependencies with:

```bash
pip install PyQt5 requests
```

---

### 🔑 Setup Your API Key

Replace this line in the code with your actual API key from OpenWeatherMap:

```python
api_key = "YOUR_API_KEY_HERE"
```

---

### 📁 How to Run

```bash
python weather_app.py
```

> Make sure you’re connected to the internet — this baby fetches live weather!

---

### 💥 Error Handling Included

This app handles all sorts of potential errors like:

- ❌ Wrong city name
- 🔐 Invalid API key
- 🔌 No internet connection
- 🧱 Server down / timeout

You'll get descriptive messages for each — no mystery crashes.

---

### 🌈 UI Vibes

Styled using native PyQt stylesheet goodness:

- Big, centered labels  
- Italic titles  
- Font-awesome emoji vibe  
- Clean as hell layout

---

### 🧠 Future Ideas (Optional)

- Add weather icons instead of just emojis  
- Show additional data like humidity/wind  
- Add support for location-based weather (via IP or GPS)  
- Dark mode toggle 🌙

---



### 📜 License

MIT License — use it, break it, fix it, ship it 💻

---
