 # Exploring Weather Trends 

The intention of this project is to observe weather trends in San Francisco and compare them to Global Weather Trends. 

### Downloading/Installing 

The project is a standard word document. SQL was used to pull weather data from a Udacity Database


## Extracting the Data 

City Data is extracted from database using following SQL query:
i.SELECT*
ii.FROM city_data
iii.WHERE city='San Francisco'

Global Data is extracted from database using following SQL query:
i.SELECT*
ii.FROM global_data

### Plotting Data & Moving Average 

Data should be exported to a .CSV file once it is correctly extracted 

In excel basic statistical data was pulled and a 10 yr moving average was created. 

The moving average was calculated and plotted on top of the actual temperature by year in order to show the overall fluctuation in temperature. 
