# Live Weather Web App

## Overview

This repository contains the code for a simple Flask web application that provides live weather information. The application uses the Weather API to fetch current weather data and a 3-day forecast for a specified location.

## Files

### 1. `app.py`

This Python script contains the main code for the Flask web application. It includes routes for the home page and a weather prediction page. The application fetches weather data from the Weather API, processes the JSON response, and renders the data on the home page.

### 2. `home.html`

This HTML file defines the structure of the home page. It includes a form for users to input a location and submit a request for weather information. The page dynamically displays weather data if available, and it handles errors gracefully if the location is invalid.

### 3. `home.css`

This CSS file styles the web application. It provides a clean and visually appealing layout for the home page, including a registration form, input field, and weather information display. The styles enhance the user experience and make the application more aesthetically pleasing.

## Instructions

1. Clone the repository.

2. Install dependencies:

   ```bash
   pip install flask requests
   ```

3. Run the application:

   ```bash
   python app.py
   ```

   The application will run on `http://127.0.0.1:5000/`.

4. Open a web browser and navigate to `http://127.0.0.1:5000/` to use the live weather web app. Enter a location in the input field and click "Search" to view the current weather and a 3-day forecast.

## Screenshots

![Screenshot 1](/UI/start.png)

![Screenshot 2](/UI/0.png)

![Screenshot 3](/UI/error.png)

![Screenshot 3](/UI/1.png)

Feel free to ask questions :)
