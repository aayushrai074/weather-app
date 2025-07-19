# Weather App

This is a simple Weather App built with **HTML**, **CSS**, and **JavaScript**. It uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch real-time weather data for any city in the world.

## Features

- Search weather by city name
- Displays temperature in Celsius
- Shows humidity and wind speed
- Updates weather icon dynamically
- Displays error message if city is not found

## Technologies Used

- HTML
- CSS (Responsive design)
- JavaScript (Async/Await, Fetch API)
- OpenWeatherMap API

## How to Use

1. Clone this repo or [Download ZIP](https://github.com/aayushrai074/weather-app/archive/refs/heads/main.zip)
2. Open the `index.html` file in your browser
3. Type a city name and click the search icon 🔍

## API Key Setup

This app uses the free **OpenWeatherMap API**. My API key is already included in the code, but if you want to use your own:

1. Sign up at [OpenWeatherMap](https://openweathermap.org/)
2. Replace the `apiKey` value inside `script` tag in `index.html`:

```js
const apiKey = "your_api_key_here";

** Project Structure**
weather-app/
├── img/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   └── wind.png
├── index.html
├── style.css
└── README.md

**Credits**
- Weather data by OpenWeatherMap
- Icons rom FlatIcon

