# python-api-challenge
It's Getting Hot in Here
Python API Homework - What's the Weather Like?
Background
Before You Begin
Part I - WeatherPy
12/14/2020 A - Homework/06-Python-APIs/Instructions/README.md · master · CW-Coding-Bootcamp / CWRU-CLE-DATA-PT-10-2020-U-C · GitLab
https://cw.bootcampcontent.com/CW-Coding-Bootcamp/cwru-cle-data-pt-10-2020-u-c/blob/master/A - Homework/06-Python-APIs/Instructions/READM… 2/4
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude
After each pair of plots, take the time to explain what the linear regression is modeling. For example, describe any
relationships you notice and any other analysis you may have.
Your final notebook must:
Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.
Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google
Places API for this part of the assignment.
Note: Remember that any API usage beyond the $200 credit will be charged to your personal account. You can
set quotas and limits to your daily requests to be sure you can't be charged. Check out Google Maps Platform
Billing and Manage your cost of use for more information.
Note: if you having trouble displaying the maps, try running jupyter nbextension enable --py gmaps in your
environment and retry.
To complete this part of the assignment,you will need to do the following:
Create a heat map that displays the humidity for every city from Part I.
heatmap
Narrow down the DataFrame to find your ideal weather condition. For example:
A max temperature lower than 80 degrees but higher than 70.
Wind speed less than 10 mph.
Zero cloudiness.
Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
Note: Feel free to adjust to your specifications but be sure to limit the number of rows returned by your API
requests to a reasonable number.
Part II - VacationPy
12/14/2020 A - Homework/06-Python-APIs/Instructions/README.md · master · CW-Coding-Bootcamp / CWRU-CLE-DATA-PT-10-2020-U-C · GitLab
https://cw.bootcampcontent.com/CW-Coding-Bootcamp/cwru-cle-data-pt-10-2020-u-c/blob/master/A - Homework/06-Python-APIs/Instructions/READM… 3/4
Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
