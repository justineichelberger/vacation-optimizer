# Vacation Optimizer
## A Python Application for Data-Driven Vacation Destination Selection
* The application is set within a [Jupyter](https://jupyter.org/) notebook
* openweathermap.org API access can be obtained [here](https://openweathermap.org/appid)
* gmaps API access/use documentation can be found [here](https://developers.google.com/maps/documentation/geocoding/get-api-key)
* This application depends on the use of the following external Python libraries:
  * [matplotlib](https://matplotlib.org/)
  * [requests](https://docs.python-requests.org/en/latest/)  
  * [pandas](https://pandas.pydata.org/)
  * [numpy](https://numpy.org/)
  * [gmaps](https://pypi.org/project/gmaps/)
  * [citipy](https://pypi.org/project/citipy/)
  * [scipy](https://www.scipy.org/) 
* API keys should be saved within the `api_keys.py` file in each application directory and should not be displayed publicly

The WeatherPy application plots various weather features as functions of latitude e.g.

![Screen Shot 2021-09-27 at 9 52 27 PM](https://user-images.githubusercontent.com/79673051/135020567-8cafdb4f-211d-435a-af1a-ba0024d1b663.png)

or 

![Screen Shot 2021-09-27 at 10 02 26 PM](https://user-images.githubusercontent.com/79673051/135021315-a10f2816-eb46-45f5-9603-966802d492f2.png)

or 

![Screen Shot 2021-09-27 at 10 11 25 PM](https://user-images.githubusercontent.com/79673051/135021954-3362fc8f-ba98-4335-97f5-66aafe8c55bf.png)

Then the VacationPy application selects locations with ideal weather conditions and finds hotels within close proximity to locations matching your ideal weather conditions using the gmaps API and displays the resulting information in a popup for each location marker e.g.

<img width="969" alt="Screen Shot 2021-09-27 at 10 21 36 PM" src="https://user-images.githubusercontent.com/79673051/135022793-54d2bed8-e7e1-4b82-92ed-d5b69bcc4530.png">

Preferred weather conditions can be edited by changing the values in each of the conditional statements within the "...fitting weather criteria" cell of the VacationPy notebook.  How else can one expect to satisfy one's extraordinarily narrow comfort range?
