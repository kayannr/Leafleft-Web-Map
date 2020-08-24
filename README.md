# Visualizing Data with Leaflet

https://kayannr.github.io/leaflet-challenge/USGS/index.html

## Background

![1-Logo](USGS/static/images/1-Logo.png)

The USGS (United States Geological Survey) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. They collect a massive amount of data from all over the world each day. This project creates a web map that displays the data gathered from the USGS website. 

## Tasks Completed 
1. **Gather data set**

   ![3-Data](USGS/static/images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. The [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page provides the URL of the JSON to pull in the data for the visualization.

  ![4-JSON](USGS/static/images/4-JSON.png)
  
 2. **Import & Visualize the Data**

   The Leaflet maps that plot all of the earthquakes from the data set based on their longitude and latitude are displayed below. The features of the maps include: 
   * Data markers that reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes  appear larger and darker in color.

   * Popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for your map data.

   * Your visualization should look something like the map above.
