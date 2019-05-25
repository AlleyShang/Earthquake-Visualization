# Unit 17 | Assignment - Visualizing Data with Leaflet

## Background

![1-Logo](Images/1-Logo.png)

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

Level-1 of the project is to visualize an earthquake data set.

1. **Data Source**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes] including GeoJSON. 
   Dataset used here is: 'All Earthquakes from the Past 7 Days'(https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) which a JSON representation of that data.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   This step creates a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

   * Data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

   * Popups are included that provide additional information about the earthquake when a marker is clicked.

   * Legend is included that will provide context for the map data.

- - -

### Level 2: More Data 

![5-Advanced](Images/5-Advanced.png)

Level-2 of this project illustrates the relationship between tectonic plates and seismic activity.

1. **Data Source**
   
   Data on tectonic plates was sourced from here: <https://github.com/fraxen/tectonicplates>.
   
2. **Import & Visualize the Data**

   In this step we are going to..

      * Plot a second data set on our map.

      * Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be      turned on and off independently.

      * Add layer controls to our map.

- - -

