## Exploratory Data Analysis
### Starbucks Advertising NYC Project
#### Marcel Colvin
**Abstract**

The main goal of this project was to use location and subway traffic data to find locations in New York City where it would be appropriate to open a new Starbucks. The second goal of this project is to find locations with high traffic and Starbucks nearby that would be good locations for targeted advertising. I worked with the NYC Metropolitan Transportation Authority (MTA) subway traffic data, geolocations of the subway stops, and the geolocations of Starbucks. After plotting and creating many visualizations I found that East Brooklyn, Northern Bronx, and the edges of Jamaica Bay would be the best locations for a new Starbucks. I also found that Lower Manhattan would be the best location for advertisements to be run in Subway stops.

**Design**

This project was designed to utilize location data to find actionable insights for Starbucks marketing. By analyzing the most visited stops and their locations relative to a Starbucks, we should be able to find subway stops that have traffic and lack a walkable Starbucks. This will allow Starbucks to be able to find areas where they can expand their stores.

**Data**

The main dataset is the MTA subway traffic data over 3 months in the summer of 2019 which was used to find the subway stops that saw the most traffic in non-covid times. This is important because I wanted a large traffic timeframe pre-covid so that Starbucks will be able to make inferences into the future when travel and commuting are regular again. This data was used in combination with the geolocations of the subway stops and the geolocations of Starbucks stores. There are about 400 subway stops and 200 Starbucks in the NYC area.

**Models**

This project was mainly about cleaning data and creating visualizations that would be useful for making insights. I was able to use these visualizations to make conclusions which Starbucks could use to open a new store or improve their targeted advertising.

**Tools**

The packages used were: Pandas (for data manipulations), Geopandas (for geospatial data manipulation and plotting), Geopy (for geospatial data manipulation), fuzzywuzzy (to facilitate fuzzy merges).

**Communication**

The main visualizations are included in my pdf presentation and appendix.
