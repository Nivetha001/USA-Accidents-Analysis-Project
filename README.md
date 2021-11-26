## US-Accidents-Analysis-Project
__________________________________________________________________________

#### Technology : Business Intelligence
#### Domain     : Transportation
### 🕵 Inspiration
____________________________________________________________________________________________________________________________
US-Accidents can be used for numerous applications such as real-time car accident prediction, studying car accidents hotspot locations, casualty analysis and extracting cause and effect rules to predict car accidents, and studying the impact of precipitation or other environmental stimuli on accident occurrence. 

![us acc](https://user-images.githubusercontent.com/79318960/143535268-17e1309f-78c8-4927-bb31-80d525eac339.png)


The most recent release of the dataset can also be useful to study the impact of COVID-19 on traffic behavior and accidents.

### ⏳ Data Description
_____________________________________________________________________________________
This Data Set Contains 1.5 Million Records in this dataset
DATA SET LINK:https://www.kaggle.com/sobhanmoosavi/us-accidents
This is a countrywide car accident dataset, which covers 49 states of the USA. The accident data are collected from February 2016 to Dec 2020.
#### Columns
____________________________________________________________________________________________________

##### 1.ID-This is a unique identifier of the accident record, 1516064 unique values
##### 2.Severity-Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic
##### 3.Start_Time-Shows start time of the accident in local time zone.
##### 4.End_Time-Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.
##### 5.Start_Lat-Shows latitude in GPS coordinate of the start point.
##### 6.Start_Lng-Shows longitude in GPS coordinate of the start point.
##### 7.End_Lat-Shows latitude in GPS coordinate of the end point.
##### 8.End_Lng-Shows longitude in GPS coordinate of the end point.
##### 9.Distance(mi)-The length of the road extent affected by the accident.
##### 10.Description-Shows natural language description of the accident.
##### 11.Number-Shows the street number in address record.
##### 12.Street-Shows the street name in address record.
##### 13.Side-Shows the relative side of the street (Right/Left) in address record.
##### 14.City-Shows the city in address record.
##### 15.Country-Shows the county in address record.
##### 16.State-Shows the state in address record.
##### 17.Zipcode-Shows the zipcode in address record.
##### 18.Timezone-Shows timezone based on the location of the accident (eastern, central, etc.).
##### 19.Airport_Code-Denotes an airport-based weather station which is the closest one to location of the accident
##### 20.Weather_Timestamp-Shows the time-stamp of weather observation record (in local time).
##### 21.Temperature(F)-Shows the temperature (in Fahrenheit).
##### 22.Wind_Chill(F)-Shows the wind chill (in Fahrenheit).
##### 23.Humidity(%)-Shows the humidity (in percentage).
##### 24.Pressure(in)-Shows the air pressure (in inches).
##### 25.Visibility(mi)-Shows visibility (in miles).
##### 26.Wind_Direction-Shows wind direction.
##### 27.Wind_Speed(mph)-Shows wind speed (in miles per hour).
##### 28.Precipitation(in)-Shows precipitation amount in inches, if there is any.
##### 29.Weather_Condition-Shows the weather condition (rain, snow, thunderstorm, fog, etc.)
##### 30.Amenity-A POI annotation which indicates presence of amenity in a nearby location.
##### 31.Bump-A POI annotation which indicates presence of speed bump or hump in a nearby location.
##### 32.Crossing-A POI annotation which indicates presence of crossing in a nearby location.
##### 33.Give_Way-A POI annotation which indicates presence of give_way in a nearby location.
##### 34.Junction-A POI annotation which indicates presence of junction in a nearby location.
##### 35.No_Exit-A POI annotation which indicates presence of junction in a nearby location.
##### 36.Railway-A POI annotation which indicates presence of railway in a nearby location.
##### 37.Roundabout-A POI annotation which indicates presence of roundabout in a nearby location.
##### 38.Station-A POI annotation which indicates presence of station in a nearby location.
##### 39.Stop-A POI annotation which indicates presence of stop in a nearby location.
##### 40.Traffic_Calming-A POI annotation which indicates presence of traffic_calming in a nearby location.
##### 41.Traffic_Signal-A POI annotation which indicates presence of traffic_signal in a nearby location.
##### 42.Turning_Loop-A POI annotation which indicates presence of turning_loop in a nearby location.
##### 43.Sunrise_Sunset-Shows the period of day (i.e. day or night) based on sunrise/sunset.
##### 44.Civil_Twilight-Shows the period of day (i.e. day or night) based on civil twilight.
##### 45.Nautical_Twilight-Shows the period of day (i.e. day or night) based on nautical twilight.
##### 46.Astronomical_Twilight-Shows the period of day (i.e. day or night) based on astronomical twilight.

### 🛠 Tools Used
_____________________________________________________________________________________________________
![gh](https://user-images.githubusercontent.com/79318960/143535805-a972b31b-a03a-4379-998d-0f1f3387a6a2.png)

#### * Pandas for Cleaning the Data
#### * Matplotlib, Seaborn for Visualization
#### * Jupyter Notebook for create and share documents that integrate live code, equations, computational output, visualizations, and other multimedia resources, along with explanatory text in a single document.

### Conclusion ✍️
___________________________________________________________________________________________________________________________
* No data from New York
* The number of accidents per city decreases exponentially
* Less than 2% of cities have more than 1000 yearly accidents.
* 97% of cities have less than 1000 yearly accidents.
* Over 1167 cities have reported just one accident (need to investigate)
