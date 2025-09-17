Weather Now App
Weather Now is a simple React-based web application that allows users to quickly check the current weather for any city.  
This project was built as part of a UI Take-Home Challenge
 Features
- Search weather by city name
- Fetches real-time data from [Open-Meteo API](https://open-meteo.com/)
- Displays temperature, wind speed, and weather condition code
- Responsive design (works on desktop & mobile)
- Error handling for invalid city names or failed requests
- Loading indicator while fetching data
🛠Tech Stack
- React (JavaScript) – Component-based UI
- CSS– Styling and responsiveness
- Open-Meteo API – Weather data
 Project Structure
weather-now-app
├── App.js # React logic + JSX
├── App.css # Styling
├── index.js # Entry point
Open-Meteo API Basics
  -Open-Meteo is a free, no-authentication weather API. You can use it to fetch weather forecasts and current weather data.

---

## 📸 Demo
1. Enter a city name in the input field.
2. Click "Check Weather".
3. View the results card showing:
   - 🌡️ Temperature
   - 💨 Wind speed
   - ☁️ Weather code
 Setup Instructions
1. Clone this repo:bash
   git clone https://github.com/your-username/weather-now-app.git
   cd weather-now-app
Install dependencies (if using create-react-app or Vite):
npm install
Start the development server:
  -npm start
The app uses Open-Meteo Geocoding API to convert city names → latitude/longitude.
Then it calls Open-Meteo Weather API to fetch current weather data.
Error messages are shown if the city is invalid or the API fails.
Designed with clean UI and responsiveness in mind.
