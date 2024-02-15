# Weather App

## Introduction

The Weather App is a simple web application built with React.js. It provides users with current weather conditions and a 5-day forecast for a specified city. The application utilizes the OpenWeatherMap API to fetch weather data.

## Features

- Display current weather information including temperature, description, and weather icon.
- Show a 5-day weather forecast with details for each day.
- Allow users to search for weather information by entering the city name.
- Clean and user-friendly interface.

## Technologies Used

- React.js
- HTML5
- CSS3
- OpenWeatherMap API

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/weather-app.git

```

2. Navigate to the project directory:

```bash
cd weather-app

```

3. Install dependencies:

```bash
npm install
```

4. Run the application:

```bash
npm start

```

5. Open your browser and go to `http://localhost:3000` to view the app.

## Usage

- Enter the name of the city you want to check the weather for in the input field.
- Press Enter or click the search button.
- View the current weather and 5-day forecast for the specified city.

## Live Demo

Check out the live demo [here](https://genuine-parfait-ada97f.netlify.app/).

## Note

To use the Weather App, you need to obtain an API key from OpenWeatherMap. Create a file named `.env` in the project root directory and add the following line, replacing `your-api-key-goes-here` with your actual OpenWeatherMap API key:

```plaintext
REACT_APP_OPENWEATHERMAP_API_KEY=your-api-key-goes-here
```
