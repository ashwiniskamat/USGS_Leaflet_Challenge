# USGS_Leaflet_Challenge

The purpose of this project is to visualize earthquake data using data collected by the United States Geological Survey (USGS).

The USGS provides earthquake data in different formats which is updated every 5 minutes. 

A data set was selected to visualize from the [USGS GeoJSON Feed] ("https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page. 

This projects analyzes and visualizes significant earthquakes in the past seven days.

A map which plots earthquakes from the data set based on their longitude and latitude was created using Leaflet. It includes...
- data markers that reflect the magnitude of the earthquake (size and depth) by color
- popups that provide additional information about a quake when a given marker is clicked
- a legend that provides context
