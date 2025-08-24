# 🌦️ Weather Forecasting Web Application

The Weather Forecasting Web Application provides real-time weather updates using API integration. Built with HTML, CSS, and JavaScript in VS Code, it displays data like temperature, humidity, and wind speed. The interface is user-friendly and responsive for seamless weather checks.

![image alt](https://github.com/MohammedNawaz07/Weather_Forecasting_Web_Application/blob/623eb8c0fb6e89355015b150c40773a4f2d73ab9/weather-app-image.png)

# 📌 Overview

The Weather Forecasting Web App provides real-time weather updates and forecasts for any city worldwide. It fetches live weather data using APIs and displays it with an intuitive, user-friendly interface.

This project demonstrates the integration of web technologies, APIs, and responsive UI design to deliver accurate weather insights.


# ✨ Features

🌍 Search weather by city name

⏱️ Real-time temperature, humidity, and wind speed updates

📅 5-day weather forecast

🎨 Clean and responsive UI design

🌙 Light/Dark mode support (optional)

📍 Location-based weather (using geolocation API, optional)


# 🛠️ Tech Stack

# Frontend

* HTML5, CSS3, JavaScript

* React.js (if built using React)

* Tailwind CSS / Bootstrap for styling

# Backend (optional)

* Node.js & Express (if used for server-side API calls)

# API Used

OpenWeatherMap API
 (for weather data)

# Tools

* VS Code (Development IDE)

* Git & GitHub (Version control)

* Netlify / Vercel / GitHub Pages (Deployment)


# 📂 Project Structure

weather-app/

│── index.html             # Main page

│── style.css              # Stylesheet

│── script.js              # API calls & logic (if vanilla JS)

│── src/                   # React source folder (if React app)

│── assets/                # Images, icons, background

│── README.md              # Documentation



# 🚀 Installation & Setup

1. Clone Repository
git clone https://github.com/your-username/weather-app.git
cd weather-app

2. Install Dependencies (if React or Node used)
npm install

3. Add API Key

Get a free API key from OpenWeatherMap

Replace YOUR_API_KEY in script.js (or .env for React/Node projects).

4. Run Project

If static: open index.html in browser

If React:

npm start


# 📊 Example API Response (OpenWeatherMap)

{
  "weather": [
    { "description": "clear sky", "icon": "01d" }
  ],
  "main": {
    "temp": 302.15,
    "humidity": 40
  },
  "wind": {
    "speed": 3.6
  },
  "name": "Bangalore"
}



# 📌 Future Enhancements

📍 Auto-detect location using geolocation API

🌡️ Show temperature in Celsius/Fahrenheit toggle

📊 Add detailed weather charts (using Chart.js or Plotly)

🛰️ Integrate satellite/radar maps



# 📜 License

This project is licensed under the MIT License – free to use, modify, and share.









