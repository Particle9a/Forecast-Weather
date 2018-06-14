#WEATHER FORECAST

Aplikasi untuk memenuhi Tugas 2 Seleksi Calon ASisten Lab Programming

oleh

Muhammad Aufa Helfiandri - 13516008

-------

### OpenWeatherMap API

API an acronym for *Application Programming Interface* is a collection of instruction and protocol that used to create a software. API is used as a messenger that accepts user request and tell system what to do based on the request. (Sumber  : http://developer.erabelajar.com/api-application-programming-interface/)

OpenWeatherMap is an API that used to get Weather Data from multiple cities in the world. OpenWeatherMap provide some API which includes *Current Weather API*, *5 day/3 hour forecast API*, *16 Day / Daily Forecast API*, and some other API.

These API give access to weather Data based on their name, for example Current Weather API provide the Data of current weather from 200,000 cities and 40,000 weather station around the world. (Sumber: https://openweathermap.org/api)

-------

### Package & Class
 Because the project is still in Planning process, the Packages and Class I listed here is still temporary and could be changed as the project is being developed.

#### Main/Default Package
 Package for Main Class.

###### Main Class
 Class to Run the Application

#### Interaction Package
 Package that handle GUI and User Interaction to Java Swing API

###### DataDisplayer Class
 Class that stores the Data that want to be Displayed

###### Menu Class
 Class that represent on screen menu to interact with user

#### Data Controller Package
 Package that handle the Data which already received to local memory.

###### CityCollection Class
 Class that handle Data of Cities that already gathered by OpenWeatherMapAPI

###### City
 Class that represent a City including it's weather Datas

###### Weather 
 Class that represent a Weather Data

#### Weather Getter Package
 Package that handle interaction with OpenWeatherMap API

###### Weather_Getter
 Class to get Data from OpenWeatherMap API


 -----

 ### Checklist

 | No  |Class Name  |Progress   |
| ------------ | ------------ | ------------ |
|   1| Main  |   |
|   2| DataDisplayer  |   |
|   3| Menu  |  |
|   4| CityCollection  |   |
|   5| City | |
|   6| Weather | |
|   7| WeatherGetter | |