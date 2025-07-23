# Climafy – Weather Forecast Web App

**Climafy** is a React-based weather app that allows users to search for any city worldwide and view real-time weather conditions along with a 5-day forecast. Built with the OpenWeatherMap and GeoDB APIs, it features a sleek UI and supports autocomplete location search.

---

## Features

- City autocomplete search using the GeoDB Cities API
- Real-time current weather and 5-day forecast via OpenWeatherMap
- Displays temperature, humidity, wind speed, pressure, and more
- Dark-themed weather card with responsive design

---

## Getting Started

### Clone the repository

```sh
git clone https://github.com/your-username/climafy.git
cd climafy
```

### Install dependencies

```sh
npm install
```

### Set up environment variables

Create a `.env` file in the root directory and add your API keys (see `.env.example` if available):

```
REACT_APP_GEO_API_KEY=your_geodb_api_key
REACT_APP_GEO_API_HOST=your_geodb_api_host
REACT_APP_GEO_API_URL=https://wft-geo-db.p.rapidapi.com/v1/geo
REACT_APP_WEATHER_API_URL=https://api.openweathermap.org/data/2.5
REACT_APP_WEATHER_API_KEY=your_openweathermap_api_key
```

### Start the development server

```sh
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000).

---

## API References

- [GeoDB Cities API](https://rapidapi.com/wirefreethought/api/geodb-cities/)
- [OpenWeatherMap API](https://openweathermap.org/api)
