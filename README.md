# Weatherly 🌤️

## Description

Weatherly is a weather forecasting application that provides users with up-to-date weather information, including temperature, humidity, wind speed, and forecasts. Built using React, Weatherly integrates the OpenWeatherMap API for weather data and GeoDB API for location search with autocomplete functionality, making it easy to find weather information for any location worldwide.

## Features

	•	Real-time weather updates for cities around the globe
	•	Autocomplete search powered by GeoDB API for seamless location lookup
	•	Display of current weather conditions and a 7-day forecast
	•	Accessible design with a user-friendly interface

## Installation

To set up the project locally, follow these steps:

### 1.	Clone the repository:

-> git clone https://github.com/your-username/weatherly.git
cd weatherly

### 2. Install Dependencies:

-> npm install

### 3.	Set up API Keys:
-> Sign up for API access from:
        **OpenWeatherMap:** https://openweathermap.org/ 
        **GeoDB Cities:** https://rapidapi.com/wirefreethought/api/geodb-cities

-> In the api.js file, add your API keys:
       i. export const geoApiOptions = {
	        method: 'GET',
	        headers: {
		          'x-rapidapi-key': 'your_api_key',
		          'x-rapidapi-host': 'wft-geo-db.p.rapidapi.com'
	          }
       };

       ii. export const WEATHER_API_KEY = 'your_api_key'

### 4.	Start the application:

-> npm start

The application will be available at http://localhost:3000.


## Technologies Used

  • **React:** UI library for building the user interface
	• **OpenWeatherMap API:** Provides weather data, including current conditions and forecasts
	•	**GeoDB Cities API:** Location search with autocomplete for a seamless user experience
	•	**React Accessible Accordion:** Accessibility-friendly accordion component

## Scripts

The project includes the following npm scripts:
	•	npm start: Runs the app in development mode.
	•	npm test: Launches the test runner.
	•	npm run build: Builds the app for production.

Dependencies

The main dependencies for this project include:
	•	@testing-library/jest-dom
	•	@testing-library/react
	•	@testing-library/user-event
	•	react (v18.3.1)
	•	react-accessible-accordion
	•	react-dom
	•	react-scripts
	•	react-select-async-paginate
	•	web-vitals

Refer to package.json for the full list of dependencies and versions.
