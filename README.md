## US-Accidents-Analysis-Project

#### Technology : Business Intelligence
#### Domain     : Transportation
### Inspiration
US-Accidents can be used for numerous applications such as real-time car accident prediction, studying car accidents hotspot locations, casualty analysis and extracting cause and effect rules to predict car accidents, and studying the impact of precipitation or other environmental stimuli on accident occurrence. 

![us acc](https://user-images.githubusercontent.com/79318960/143535268-17e1309f-78c8-4927-bb31-80d525eac339.png)


The most recent release of the dataset can also be useful to study the impact of COVID-19 on traffic behavior and accidents.

### Data Description
This Data Set Contains 1.5 Million Records in this dataset
DATA SET LINK:https://www.kaggle.com/sobhanmoosavi/us-accidents
This is a countrywide car accident dataset, which covers 49 states of the USA. The accident data are collected from February 2016 to Dec 2020.
##### ID-This is a unique identifier of the accident record, 1516064 unique values
##### Severity-Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic
##### Start_Time-Shows start time of the accident in local time zone.
##### End_Time-Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.
##### Start_Lat-Shows latitude in GPS coordinate of the start point.
##### Start_Lng-Shows longitude in GPS coordinate of the start point.
##### End_Lat-Shows latitude in GPS coordinate of the end point.
##### End_Lng-Shows longitude in GPS coordinate of the end point.
##### Distance(mi)-The length of the road extent affected by the accident.
##### Description-Shows natural language description of the accident.
##### Number-Shows the street number in address record.
##### Street-Shows the street name in address record.
##### Side-Shows the relative side of the street (Right/Left) in address record.
##### City-Shows the city in address record.
##### Country-Shows the county in address record.
##### State-Shows the state in address record.
##### Zipcode-Shows the zipcode in address record.
##### Timezone-Shows timezone based on the location of the accident (eastern, central, etc.).
##### Airport_Code-Denotes an airport-based weather station which is the closest one to location of the accident
##### Weather_Timestamp-Shows the time-stamp of weather observation record (in local time).
##### Temperature(F)-Shows the temperature (in Fahrenheit).
##### Wind_Chill(F)-Shows the wind chill (in Fahrenheit).
##### Humidity(%)-Shows the humidity (in percentage).
##### Pressure(in)-Shows the air pressure (in inches).
##### Visibility(mi)-Shows visibility (in miles).
##### Wind_Direction-Shows wind direction.
##### Wind_Speed(mph)-Shows wind speed (in miles per hour).
##### Precipitation(in)-Shows precipitation amount in inches, if there is any.
##### Weather_Condition-Shows the weather condition (rain, snow, thunderstorm, fog, etc.)
##### Amenity-A POI annotation which indicates presence of amenity in a nearby location.
##### Bump-A POI annotation which indicates presence of speed bump or hump in a nearby location.
##### Crossing-A POI annotation which indicates presence of crossing in a nearby location.
##### Give_Way-A POI annotation which indicates presence of give_way in a nearby location.
##### Junction-A POI annotation which indicates presence of junction in a nearby location.
##### No_Exit-A POI annotation which indicates presence of junction in a nearby location.
##### Railway-A POI annotation which indicates presence of railway in a nearby location.
##### Roundabout-A POI annotation which indicates presence of roundabout in a nearby location.
##### Station-A POI annotation which indicates presence of station in a nearby location.
##### Stop-A POI annotation which indicates presence of stop in a nearby location.
##### Traffic_Calming-A POI annotation which indicates presence of traffic_calming in a nearby location.
##### Traffic_Signal-A POI annotation which indicates presence of traffic_signal in a nearby location.
##### Turning_Loop-A POI annotation which indicates presence of turning_loop in a nearby location.
##### Sunrise_Sunset-Shows the period of day (i.e. day or night) based on sunrise/sunset.
##### Civil_Twilight-Shows the period of day (i.e. day or night) based on civil twilight.
##### Nautical_Twilight-Shows the period of day (i.e. day or night) based on nautical twilight.
##### Astronomical_Twilight-Shows the period of day (i.e. day or night) based on astronomical twilight.

### Tools Used

![gh](https://user-images.githubusercontent.com/79318960/143535805-a972b31b-a03a-4379-998d-0f1f3387a6a2.png)

#### * Pandas for Cleaning the Data
#### * Matplotlib, Seaborn for Visualization
#### * Jupyter Notebook for create and share documents that integrate live code, equations, computational output, visualizations, and other multimedia resources, along with explanatory text in a single document.

### Conclusion
* No data from New York
* The number of accidents per city decreases exponentially
* Less than 2% of cities have more than 1000 yearly accidents.
* 97% of cities have less than 1000 yearly accidents.
* Over 1167 cities have reported just one accident (need to investigate)
