This file is to create an EnergyPlus weather file (.epw) from scratch. 

The software [Elements](https://bigladdersoftware.com/projects/elements/) is required to create the first empty .epw file, to transform it to a .csv file, and afterwards compile again the final .epw file. The .csv file is edited using Python with the provided script. The data about the location (altitude, latitude, longitude, etc.) is defined within Elements. The advantage of using Elements is that the psycrometric relationship between the variables is guaranteed. 

In this case, the weather file for Weihenstephan (Germany) for the year 2021 was created. The weather data was obtained from the measurements in the weather station of the German Weather Service (*Deutscher Wetterdienst*), and downloaded from their [CDC Server](https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/). 

The following libraries were used:
- Pandas
- Numpy 
- Matplotlib
- Scikit-learn

