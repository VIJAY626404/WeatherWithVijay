# WeatherWithVijay 🌤️

Welcome to the WeatherWithVijay app! This Flask-based web application fetches real-time weather data using the OpenWeather API and displays it in a user-friendly format.

## Project Overview

This project is a simple weather application where users can input the name of a city, and the app will return current weather details such as temperature, humidity, and more. The application is powered by the Flask web framework and uses the OpenWeather API to retrieve weather data.

## Features

- 🌍 Get real-time weather updates for any city in the world.
- 🔥 Choose between different units (e.g., Celsius or Fahrenheit).
- 💻 Simple and clean UI for a seamless user experience.

## Demo

Below are some example outputs from the application:

<img src="https://github.com/VIJAY626404/WeatherWithVijay/blob/main/Outputs/1.png" alt="Output Example" width="900"/>
<img src="https://github.com/VIJAY626404/WeatherWithVijay/blob/main/Outputs/2.png" alt="Output Example" width="900"/>
<img src="https://github.com/VIJAY626404/WeatherWithVijay/blob/main/Outputs/3.png" alt="Output Example" width="900"/>

## Getting Started

### Prerequisites

Make sure you have Python installed in your environment. The project requires the following Python libraries, which are listed in the `requirements.txt` file.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/VIJAY626404/WeatherWithVijay.git
   cd WeatherWithVijay
   ```
2. **Install the dependencies:**
  ``` bash
   pip install -r requirements.txt
```
3. **Install the dependencies:**
  ``` bash
   pip install -r requirements.txt
```
## Running the Application
1. **Start the Flask server:**
``` bash
python app.py
```
2. **Open your browser and navigate to:**
``` bash
[python app.py](http://localhost:5002/)
```
## How It Works
- The user inputs the name of a city.
- The app sends a request to the OpenWeather API to fetch the current weather data for that city.
- The weather data is displayed on the screen in a readable format.
## API Reference
- This application uses the OpenWeather API to fetch weather data.
- **Base URL:** https://api.openweathermap.org/data/2.5/weather
- **API Key:** You'll need your own API key to access the OpenWeather API. Replace datakey in app.py with your API key.
## Folder Structure
- **app.py:** The main Flask application file.
- **requirements.txt:** A list of dependencies required to run the application.
- **Outputs:** A folder containing screenshots of the app’s output.
  
## Technologies Used
- **Flask:** For creating the web application.
- **Requests:** For sending HTTP requests to the OpenWeather API.
- **Gunicorn:** For deployment in production environments.
  
## Future Enhancements
- 🌐 **Expand to multiple weather endpoints:** Fetch not only current weather but also forecast data.
- 📊 **Visualizations:** Add charts and graphs to visualize weather data more effectively.
- 🎨 **UI/UX Improvements:** Enhance the user interface with better design and interactivity.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- OpenWeather API for providing the weather data.
- Flask community for the amazing framework.
  
Feel free to contribute to this project by creating issues or submitting pull requests. Happy coding! 😎
