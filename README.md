# Weather Dashboard #

## Overview
This Weather Dashboard is a Flask-based web application that allows users to get current weather information for any city using the OpenWeatherMap API. It's designed to demonstrate Flask routing, API integration, and dynamic content rendering using Jinja2 templates.

## Features
- **Weather Lookup**: Users can search for weather data by city name.
- **Responsive Design**: Basic HTML/CSS that can be expanded for mobile responsiveness.
- **Environment Safe**: Uses environment variables to secure the API key.

## Technologies Used
- **Python 3**: Primary programming language
- **Flask**: Web framework used to create the application
- **Jinja2**: Templating engine for rendering views
- **Requests**: Library used to handle HTTP requests to the OpenWeatherMap API

## Getting Started

### Prerequisites
- Python 3.6 or higher
- pip for installing dependencies



### Installation  ###

1. **Clone the repository**

   git clone https://github.com/Sree-026/weather-dashboard.git

   cd weather-dashboard

2. Set up a virtual environment (optional but recommended):
	
	python -m venv venv source venv/bin/activate # For Windows use `venv\Scripts\activate` 


3. Install the required packages:
	
	pip install -r requirements.txt 


4.	Set up the environment variables:

•	For Linux/macOS: export OPENWEATHER_API_KEY='Your_OpenWeatherMap_API_Key' 

•	For Windows: set OPENWEATHER_API_KEY=Your_OpenWeatherMap_API_Key 



*** can create API keys for free ' https://home.openweathermap.org ' ***


Running the Application

Run the application using: flask run 

Navigate to http://127.0.0.1:5000/ in your web browser to view the application.

Deployment

This application can be deployed on various platforms like Heroku, AWS, or Azure. Ensure you set the environment variables in the deployment platform.

Contributions are welcome! Please feel free to submit a Pull Request.


Project Link: https://github.com/Sree-026/Weather-Dashboard
