# Studio Take-home

As part of our application process, we'd like to see what you can produce by giving you a small assignment. Any extra polish or features you might want to put in will not go unnoticed.

## The assignment

We would like you to perform data science style analysis on the following data. 

This data has been gathered at two solar power plants over a 30+ day period. It has two pairs of files - each pair has one power generation dataset and one sensor readings dataset. The power generation datasets are gathered at the inverter level - each inverter has multiple lines of solar panels attached to it. The sensor data is gathered at a plant level - single array of sensors optimally placed at the plant.

There are a few areas of concern at the solar power plant that we would like you to perform analysis on -

 - [ ] Can we predict the power generation for next couple of days? - this allows for better grid management
 - [ ] Can we identify the need for panel cleaning/maintenance?
 - [ ] Can we identify faulty or suboptimally performing equipment?


#### Extra credit features

 - [ ] Document critical thinking
 - [ ] Any additional questions besides the above mentioned that you think could be relavent with the provided data.


## About the Dataset:

- Dataset consist of 2 tables:

  - Plant_2_Generation_Data.csv
  - Plant_2_Weather_Sensor_Data.csv

- Plant_2_Generation_Data consist of following features:

  - DATE_TIME - Date and time for each observation. Observations recorded at 15 minute intervals.
  - PLANT_ID - Power plant ID.
  - SOURCE_KEY - Stands for the inverter id.
  - DC_POWER - Amount of DC power generated (kW) by the inverter (source_key) in this 15 minute interval.
  - AC_POWER - Amount of AC power generated (kW) by the inverter (source_key) in this 15 minute interval.
  - DAILY_YIELD - Cumulative sum of power generated on that day, till that point in time.
  - TOTAL_YIELD - Total yield for the inverter (source_key) till that point in time.

- Plant_2_Weather_Sensor_Data consist of the following features:

  - DATE_TIME - Date and time for each observation. Observations recorded at 15 minute intervals.
  - PLANT_ID - Power plant ID.
  - SOURCE_KEY - Stands for the sensor panel id. This is common for the entire file because there's only one sensor panel for collecting weather data the plant.
  - AMBIENT_TEMPERATURE - Ambient temperature at the plant.
  - MODULE_TEMPERATURE - There's a module (solar panel) attached to the sensor panel. This is the temperature reading for that module.
  - IRRADIATION - Amount of irradiation.


## Requirements

Upload your solutions to Notebook and share the output.

If you have any questions, please ask!

To submit your solution, please let your recruiter know, and give karthik20522 (github user) access to your **private repo** so that we can review and run it.
