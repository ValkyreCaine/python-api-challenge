# python-api-challenge

Hello and welcome to my Python Api Project for UCI Data Analytics BootCamp! 

In my files you will find both notebooks for WeatherPy and VacationPy. In my Output Data sub-folder you will find all of my PNG's for all plots made for WeatherPy and the cities.csv that was generated in my search.

This project aims to answer the question, why does it get hotter towards the equator? Using Citipy and the OpenWeatherMap API I set out to answer that question by running analyses on the relationships between latitude and temperature, humidity, cloudiness, and wind speed. 
I seperated it out even further by northern and southern hemispheres to conclude the following analyses:

As expected the northern hemisphere shows a clear connection with colder tempertures the higher the latitude as it is farthest from the equator. The southern hemisphere shows higher temperatures closer to the equator or 0 latitude.
There is less correlations to be made between humidity and latitude than compared to tempuratures. There is a slight connection between the equator and humiditiy. This is demonstrated to us by the plot and the r squared values support a lack of connection. Within the northern hemisphere there is a 24% variance connection to humidity and 34% variance connection in the southern hemisphere. This is not enough to make a determiniation on how humidity impacts latitudal points.
There is a fair amount of distrubtion between both hemisphere when considering cloudiness. The northern hemisphere is more dense and suggests more climatic diversity in it's regions as we have instances of 0% clouds and 100% clouds between 10 and 70 latitudes. The southern hemisphere shows more cloudiness towards the equator than further away.
There seems to be a closer relationship between lower windspeeds of 6 mph and lower near the equator within both hemispheres. While the distribution is more dense in the Northern Hemisphere, the trends seems to have a few outliers. As seen in the Northern Hemisphere there is near no connection to wind speed and latitude with a -5% r value. In the Southern hemisphere there is a -29% r value which is not strong enough to make a definitive connection between the wind speed and latitude.

I desire that more data be collected in regards to geographic phenomena in the areas studied to provide further information to support these outcomes. 

After the weather study, I then focused on places to vacation based on the previously reviewed data. I wanted a place between 6 and 34 degrees celcius, with windspeeds upwards of 3 MPH, and cloudiness less than or equal to 50 to get a list of cities I may want to visit. With that list I used geoapify to find the nearest hotels to those areas, add their name to a column in dataframe and then created a map showcasing those hotels. 
