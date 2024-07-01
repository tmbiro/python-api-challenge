# Python API Challenge
# What's the Weather Like?

## Part 1: WeatherPy

In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library Links to an external site, the OpenWeatherMap API Links to an external site, and my problem-solving skills to create a representative model of weather across cities.

For this part, I used the WeatherPy.ipynb Jupyter notebook provided above. 

**Requirement 1:** Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the WeatherPy.ipynb code. Then, I created a series of scatter plots to showcase the following relationships:

* Latitude vs. Temperature

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/bcda4229-45c4-4b6b-92e4-ec277f38b099)

* Latitude vs. Humidity

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/fb28629b-4252-492d-8468-81a2008b460d)

* Latitude vs. Cloudiness

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/ddee22d7-1972-4010-89d0-af1ec6269802)

* Latitude vs. Wind Speed

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/79e3b6ea-2bcc-45d3-ae41-b9c0b7832940)


**Requirement 2:** Compute Linear Regression for Each Relationship
To fulfill the second requirement, I computed the linear regression for each relationship. I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 

Next, I created a series of scatter plots. I included the linear regression line, the model's formula, and the r values for the following plots:

* Northern Hemisphere - Temperature (F) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/0131e327-8b8b-46c7-9fb4-9573c0e67ce8)
  
  The correlation coefficient is -0.85. 
  For cities located in the northern hemisphere, as latitude increases, temperature decreases.

* Southern Hemisphere - Temperature (F) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/891c4f27-90dc-4dcf-bf52-a328fa0df4b2)
  
  The correlation coefficient is 0.42. 
  For cities in the southern hemisphere, as latitude increases, temperature increases.

* Northern Hemisphere - Humidity (%) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/9a451d52-58f2-4cbe-8f15-21f6249199aa)
  
  The correlation coefficient is 0.4. 

* Southern Hemisphere - Humidity (%) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/f4508b3f-9e9f-4565-b91a-730daddec320)
  
  The correlation coefficient is 0.43. 
  Regardless of what hemisphere a city is located, when latitude increases, so too does humidity.

* Northern Hemisphere - Cloudiness (%) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/553bf29d-bbea-4cbb-898c-cc3aecac2838)
  
  The correlation coefficient is 0.27. 

* Southern Hemisphere - Cloudiness (%) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/b5cadccb-11a1-498d-bf14-09b1a4209dfd)
  
  The correlation coefficient is 0.41. 
  Regardless of what hemisphere a city is located, cloudiness increases with city latitude.

* Northern Hemisphere - Wind Speed (mph) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/fbc29834-e202-4f04-a386-f73a2afb0517)

  The correlation coefficient is 0.04. 
  Wind speed does not appear to be influenced by latitude changes for cities located in the northern hemisphere.

* Southern Hemisphere - Wind Speed (mph) vs. Latitude

![image](https://github.com/tmbiro/python-api-challenge/assets/26468137/45037903-75c9-4762-b30b-02435f50135d)
  
  The correlation coefficient is -0.29.
  For cities in the southern hemisphere, wind speed decreases as latitude increases.


## Part 2: VacationPy

In the VacationPy.ipynb, I used my weather data skills to plan future vacations. I also used Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Here is a map that displays a point for every city in the city_data_df DataFrame. The size of the point is the humidity in each city.
<img width="1101" alt="image" src="https://github.com/tmbiro/python-api-challenge/assets/26468137/9995a55f-1dec-400f-9754-46eb38a43108">

