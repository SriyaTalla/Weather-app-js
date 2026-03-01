# Weather-app-js

A simple web application that shows real-time weather information for any city using a public weather API.

## Features

* Search weather by city name
* Displays temperature, humidity and wind speed
* Dynamic UI update without page refresh
* Error message for invalid city

## Tech Stack

* HTML
* CSS
* JavaScript
* Fetch API
* JSON

## How It Works

When the user enters a city and clicks search, the app sends an HTTP GET request to a weather API using `fetch()`.
The server returns weather data in JSON format, which is parsed and displayed on the webpage using DOM manipulation.

## Learning Outcomes

* API integration in JavaScript
* Async/await and fetch()
* DOM manipulation
* Basic error handling
