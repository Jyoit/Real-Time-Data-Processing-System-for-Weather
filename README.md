# Weather Data Retrieval and Analysis System

## Overview

This project is designed to retrieve weather data from the OpenWeatherMap API at configurable intervals, convert temperature values based on user preference, and provide daily weather summaries, including additional parameters like humidity and wind speed. The system is built to be robust, easy to set up, and extendable.

---

## Features

- **System Setup:** Initializes and connects to the OpenWeatherMap API using a valid API key.
- **Data Retrieval:** Retrieves and parses weather data for specified locations at configurable intervals.
- **Temperature Conversion:** Converts temperature values from Kelvin to Celsius or Fahrenheit based on user preference.
- **Daily Weather Summary:** Provides weather updates over several days, calculates average, maximum, and minimum temperatures, and identifies dominant weather conditions.
- **Additional Parameters:** Retrieves additional weather parameters such as humidity and wind speed.
- **5-day Weather Forecast:** Offers a forecast of weather conditions for the next 5 days.

---

## Design Choices

- **Modularity:** The system is divided into distinct modules for initialization, data retrieval, temperature conversion, and summary generation, making it easy to maintain and extend.
- **Configurability:** API call intervals and temperature units can be configured for flexibility.
- **Extensibility:** The system is designed to easily add more weather parameters from the OpenWeatherMap API.

---

## Requirements

- Minimum screen resolution: 1070x680
- **Node.js** (optional if the system lacks live server utility)

---

## Getting Started

### Prerequisites

- Ensure you have **Node.js** and **npm** installed.


 
