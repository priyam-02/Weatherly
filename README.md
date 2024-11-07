# Weatherly 🌤️

## Description

Weatherly is a weather forecasting application that provides users with up-to-date weather information, including temperature, humidity, wind speed, and forecasts. Built using React, Weatherly integrates the OpenWeatherMap API for weather data and GeoDB API for location search with autocomplete functionality, making it easy to find weather information for any location worldwide.

## Features

	•	Real-time weather updates for cities around the globe
	•	Autocomplete search powered by GeoDB API for seamless location lookup
	•	Display of current weather conditions and a 7-day forecast
	•	Accessible design with a user-friendly interface

## Demo

https://github.com/user-attachments/assets/df06eec5-14c0-45bc-a718-fb913bccd53a



## Screenshots

#### 
<img width="1512" alt="Screenshot 2024-11-07 at 11 32 24 AM" src="https://github.com/user-attachments/assets/b12c4b93-5505-4aca-89a0-720f713c78ad">


####
<img width="1512" alt="Screenshot 2024-11-07 at 11 32 32 AM" src="https://github.com/user-attachments/assets/c63e1860-42a5-4307-be74-ebaa2f6521bf">


####
<img width="1512" alt="Screenshot 2024-11-07 at 11 34 17 AM" src="https://github.com/user-attachments/assets/9b305d58-91b9-4f45-b0d6-8c62f256ece9">




## Installation

To set up the project locally, follow these steps:

### 1.	Clone the repository:

1. git clone https://github.com/your-username/weatherly.git
2. cd weatherly

### 2. Install Dependencies:

-> npm install

### 3.	Set up API Keys:

-> Sign up for API access from:

1. **OpenWeatherMap:** https://openweathermap.org/
2. **GeoDB Cities:** https://rapidapi.com/wirefreethought/api/geodb-cities
	
-> In the api.js file, add your API keys:

1. 'x-rapidapi-key': 'your_api_key',
2. WEATHER_API_KEY = 'your_api_key'

### 4.	Start the application:

-> npm start

The application will be available at http://localhost:3000.


## Technologies Used

1. **React:** UI library for building the user interface
2. **OpenWeatherMap API:** Provides weather data, including current conditions and forecasts
3. **GeoDB Cities API:** Location search with autocomplete for a seamless user experience
4. **React Accessible Accordion:** Accessibility-friendly accordion component

## Scripts

The project includes the following npm scripts:
1. npm start: Runs the app in development mode.
2. npm test: Launches the test runner.
3. npm run build: Builds the app for production.

## Dependencies

The main dependencies for this project include:

1. @testing-library/jest-dom
2. @testing-library/react
3. @testing-library/user-event
4. react (v18.3.1)
5. react-accessible-accordion
6. react-dom
7. react-scripts
8. react-select-async-paginate
9. web-vitals

Refer to package.json for the full list of dependencies and versions.

