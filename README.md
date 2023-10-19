# AI4SG
The goal of this study is to analyse the datset "World Air Quality Index by City and Coordinates" available at  the [link](https://www.kaggle.com/datasets/adityaramachandran27/world-air-quality-index-by-city-and-coordinates) and built a complex network of territorial similarities.

The dataset contains measurements of 4 pollutants acquired in different cities of the world:
+ PM2.5: PM2.5 refers to tiny particles or droplets in the air that are 2.5 micrometers or less in width. They can be harmful to human health when inhaled, especially in high concentrations.
+ Ozone: Ozone is a gas that can form in the atmosphere through a chemical reaction between sunlight and other pollutants. High levels of ozone can be harmful to human health, particularly for those with respiratory issues.
+ Carbon Monoxide (CO): CO is a colorless, odorless gas that is produced by the incomplete burning of fossil fuels. High levels of CO can be toxic to humans and can cause headaches, dizziness, and nausea

The data are used to measure the Air Quality Index or AQI and defined by a range based on the measurements of 4 pollutants:
+ good: <50
+ moderate: 51-99
+ unhealthy for sensitive groups: 100-149
+ unhealthy: 150-200
+ very unhealthy: 201-300
+ hazardous: >300

In the second part of this case of study a second dataset has been analysed [link](https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023?resource=download).
The dataset was analysed in order to build the links dataframe for the construction of the network of territorial similarities. The weights were calculated using the Kendall correlation index between the countries.

The "Global Country Information Dataset 2023" contains a wealth of information about all countries worldwide, covering a wide range of indicators and attributes. It encompasses demographic statistics, economic indicators, environmental factors, healthcare metrics, education statistics, etc.

Finally, the map of territorial similaties was built using Gephi software.

ATC: On GitHub, the HTML representation is unable to render, please try loading the project page with nbviewer.org.
