This activity has 2 parts: WeatherPy and VacationPy
Part 1: WeatherPy

1. We used the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site.
2. We used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code
3. From this data we craeted a dataframe called " city_data_df"
4. We created a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

5. Calculate Linear Regression for Each Relationship. Separate plots for Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). We created a series of scatter plots including the linear regression line, the model's formula, and the r values: 
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude
We also saved the plots in .png format for ease of viewing
A brief analysis for each regression is note below each plot 

Part 2: VacationPy

1. We used the geoViews Python library, and the Geoapify API.
2. The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help us get started.
3. Firstly we import the city_data_df we created in the weatherpy challenge & use it to create a geoview map of different cities data with the humidity in each city.
4. Then we narrowed down the city_data_df DataFrame to find your ideal weather condition lower than 27 degrees.
5. Then we copied the city_data_df into a new dataframe called "hotel_df" to store the city, country, coordinates, and humidity.
6. Then we used the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
7. Then we added the hotel name and the country as additional information in the hover message for each city on the map.