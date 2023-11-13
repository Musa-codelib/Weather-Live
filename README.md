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

## UI/Web-app/Screenshots

![start](https://github.com/Musa-codelib/Weather-Live/assets/136096862/8e1a8b11-6bd2-47ad-9797-6762237c0c31)

![0](https://github.com/Musa-codelib/Weather-Live/assets/136096862/f14a2d34-af5e-4673-a2b8-3a58a11b2985)

![error](https://github.com/Musa-codelib/Weather-Live/assets/136096862/0ea19f4c-ee2f-4e71-9225-a910dfa54732)

![1](https://github.com/Musa-codelib/Weather-Live/assets/136096862/90262330-e158-4186-8019-a065fae153eb)

Feel free to ask questions :)
