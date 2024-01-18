# python api challlenge
## Background
Data's true power lies in its ability to definitively answer questions. In this project, we aim to answer a fundamental question: "What is the weather like as we approach the equator?" Using Python requests, APIs, and JSON traversals, we'll analyze weather data from over 500 cities of varying distances from the equator.

### Before You Begin
Create a new repository for this project called python-api-challenge. Do not add this homework to an existing repository.
Clone the new repository to your computer.
Create a directory for this assignment inside your local Git repository, named according to the challenges, such as WeatherPy.
Inside the created folder, add the files api_keys.py, WeatherPy.ipynb, and VacationPy.ipynb from the starter code ZIP file. These scripts will be the main tools for each analysis.
Add a .gitignore file to prevent sharing sensitive information like API keys.
Add the api_keys.py file to the .gitignore file to secure your API key.

### Part 1: WeatherPy
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Use the OpenWeatherMap API to retrieve weather data for cities generated in the starter code.
Create scatter plots showcasing the relationships between latitude and various weather variables:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Requirement 2: Compute Linear Regression for Each Relationship
Compute linear regression for each relationship.
Separate the plots into Northern Hemisphere and Southern Hemisphere.
Create scatter plots with linear regression lines, model formulas, and r values.

### Part 2: VacationPy
Task 1: Create a Map Displaying Points for Every City
Use Jupyter notebooks, the GeoViews Python library, and the Geoapify API.
Display a map with points for every city in the city_data_df DataFrame. The size of the point should represent the humidity in each city.
Task 2: Narrow Down Data to Ideal Weather Conditions
Filter the city_data_df DataFrame to find cities with ideal weather conditions.
Task 3: Create a New DataFrame for Hotels
Create a new DataFrame called hotel_df to store city, country, coordinates, and humidity.
Task 4: Use Geoapify API to Find Hotels
For each city, use the Geoapify API to find the first hotel within 10,000 meters of coordinates.
Task 5: Display Map with Hotel Information
Add hotel name and country as additional information in the hover message for each city on the map.


This project combines Python coding skills, API usage, and data visualization to answer questions about weather conditions and plan future vacations.
