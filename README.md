# Project-3-In-Search-of-Clear-Skies


![image](https://globalnews.ca/wp-content/uploads/2021/10/CP17269726.jpg?quality=85&strip=all)



### What is Air Quality Index ?

The Air Quality Index is a scale designed to convey the current state of air quality to people in easily comprehensible terms. It converts the complex air quality data of different pollutants into a numerical value (index value), terminology and colour. The main objective of the AQI is to inform and caution the public about the risk of exposure to daily pollution levels.

#### Monitoring Air Quality

To support the Air Quality Health Index (AQHI),there are 5 common pollutants including:

##### 🔶 Ozone 
O3 is a colourless, odourless gas at ambient concentrations and a major smog component. O3 irritates the respiratory tract and eyes. Exposure to high levels results in chest tightness, coughing and wheezing. People with respiratory and heart problems are at a higher risk. Ozone has been linked to increased hospital admissions and premature death. Ozone causes annual agricultural crop loss in Ontario and noticeable leaf damage in many crops, garden plants and trees.


##### 🔶 Particulate Matter PM 10 & PM 2.5
Particulate matter is characterized according to size - mainly because of the different health effects associated with particles of different diameters. Particulate matter is the general term used for a mixture of solid particles and liquid droplets in the air. PM 10 & PM2.5 material is primarily formed from chemical reactions in the atmosphere and through fuel combustion. Major sources include motor vehicles, smelters, power plants, industrial facilities, residential fireplaces and wood stoves, agricultural burning and forest fires.


##### 🔶 Nitrogen dioxide
NO2 is a reddish-brown gas with a pungent and irritating odour. It transforms in the air to form gaseous nitric acid and toxic organic nitrates. NO2 also plays a major role in atmospheric reactions that produce ground-level ozone, a major component of smog.

##### 🔶 Sulphur dioxide
SO2 is a colourless gas. It smells like burnt matches. It can be oxidized to sulphur trioxide, which is readily transformed into sulphuric acid mist in the presence of water vapour. Major sources of SO2 include smelters, industrial processes (e.g. petroleum refining, cement and concrete manufacturing) and electric utilities. Lesser sources of SO2 include transportation and miscellaneous/residential sources.


##### 🔶 Carbon monoxide 
CO is a colourless, odourless and tasteless but poisonous gas produced primarily by the incomplete burning of fossil fuels. Carbon monoxide is produced primarily by the incomplete combustion of fossil fuels. The transportation sector is the main source of CO emissions.


### Project Goal

The team's approach was to visualize air quality in a meaningful way to a user interacting with your website.  There are approximately 30 operating air quality stations in Southern Ontario, which collect readings on an hourly basis.  Open source API data available at https://aqicn.org/ and drawn from the Ontario Ministry of the Environment air quality data allowed the team to establish the framework for our project.  We wanted to establish a tool for users to track air quality, and also visualize how air quality is impacted by factors, including abundance of green spaces, or proximity to energy production (ie. power plants).

This group project showcases knowledge of Leaflet, JavaScript and other programming languages studied while at the U of T Data Anaytics Bootcamp. The team is studying AQI in Ontario in respect to proximity to parks and power plants using Leaflet. The team used a variety of tools, including JavaScript, HTML, Python Flask-Powered APIs, etc. to visualize different aspects of air quality, including chart types from Canvas library to show Gauge meter for AQI levels using live data and forecast data for weather and Pollutants levels.


### Project Scope:

🔶 Location : Southern Ontario

🔶 Latitude and Longitude boundaries : 42.895460, -82.513621, 46.595439, -76.031763

🔶 Data type : Live/real-time and historical (static)


### Resources:

#### Data Source:

🔶 Powerplants stations Datasets: https://datasets.wri.org/dataset/globalpowerplantdatabase 

🔶 Parks Data: https://www.geoapify.com/places-api

🔶 Air Quality Datasets: Scraped from http://www.airqualityontario.com/history/summary.php , API from https://openweathermap.org/ , https://aqicn.org/map/canada/

Tools:

🔶 Applications: Visual Studio, Python Flask-Powered APIs, PostGreSQL

🔶 Language:  Python, SQL, HTML, JavaScript, CSS

🔶 Library: Pandas, SQLAlchemy, Flask, Psycopg2, D3, Leaflet, MarkerClusters, Custom Icons, OpenLayers, Canvas, JQuery (JavaScript Library)

🔶 Visualization: Leaflet, MarkerCluster Plugin, Custom Icons and Markers, HTML/CSS/Bootstrap/Javascript, Dropdown Menu, Custom Gauge


### Project Outcomes:

When managing the deliverables and creating our dashboard, we took into consideration several factors:
* Sources of data: because we were using more than one data source, we had to ensure that the data was open source, compatible, complementary and could operate seamlessly across our dashboard.
* We paid close attention to the user interaction with our dashboard and the number of events that would be initiated by the user's selection from a drop down box.
* We sought to provide a meangingful and interesting story with our visualizations.


### Limitations: 

* Notably we have to host live server for CORS policy on weather/pm forecast
* Cannot host the Flask API/PostgreSQL DB live on Github without additional user interfaces


### Link to presentation (slides):
* https://docs.google.com/presentation/d/1pxP8dBJHFax09VCCcVRf4HO0COl5qjW0SMa2feWIzf0/edit?usp=sharing


### Team Members

Benjamin Kidston, Chu Nguyen Kien, Gauri Gupta, Michelle Carvalho


### Demo:
![](https://github.com/guptga/Project-3-In-Search-of-Clear-Skies/blob/b18eb9ae57ff6ca464e9537e79600629f48f9935/Images/AQI%20Screen%20Capture.gif)
