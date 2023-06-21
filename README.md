# Weather App

This is a simple weather forecasting application that provides a 5-day weather forecast for a given city. The app retrieves weather data from OpenWeatherMap API and visualizes it using Streamlit, Matplotlib, and Plotly.

## Features

- Displays the 5-day weather forecast for a specific city.
- Allows selection of temperature unit (Celsius or Fahrenheit).
- Provides two types of graphs: line graph and bar graph.
- Shows additional weather updates such as fog, rain, storm, snow, tornado, hurricane, cloud coverage, wind speed, sunrise, and sunset times.

## Installation

1. Clone the repository:

```
git clone https://github.com/devdigger/Weather-app.git
```


2. Change into the project directory:

```
cd Weather-app
```

3. Install the dependencies:
```
pip install -r requirements.txt
```

4. Run the application:

```
streamlit run app.py
```

## Usage

1. Enter the name of the city in the text input field.
2. Select the temperature unit (Celsius or Fahrenheit) from the dropdown menu.
3. Choose the graph type (line graph or bar graph) from the dropdown menu.
4. Click the "SUBMIT" button to display the weather forecast and additional weather updates.
5. The graph will be displayed along with the minimum and maximum temperatures for each day.
6. Additional weather updates such as fog, rain, storm, snow, tornado, hurricane, cloud coverage, wind speed, sunrise, and sunset times will be shown below the graph.

## Dependencies

The following dependencies are used in this project:

- pytz
- pyowm
- streamlit
- matplotlib
- plotly

Make sure to install these dependencies before running the application.


## Acknowledgements

- The weather data is provided by [OpenWeatherMap](https://openweathermap.org/).
