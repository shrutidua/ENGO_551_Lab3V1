# ENGO_551_Lab3V1

This Lab utilizes the City of Calgary's API to allow users to search through database for building permits. This lab utilizes Leaflet for the map and GeoJson to
access the API.

Once the broswer is opened, the map is zoomed into the City of Calgary.
Users can select dates using the calender feature to search through for databases issued during that time period. 
Users can zoom in on markers displayed on the map and select specific ones to view details such as Date Issues, Community name etc.

CONTINUING FOR LAB 4:

The Traffic Incidents Dataset was downloaded from the following link as a CSV: https://data.calgary.ca/Transportation-Transit/Traffic-Incidents-Archive-2017/himp-urp7/data

Using MapBox a tile layer was created, where the Traffic Incidents 2017 CSV was uploaded.
The data is displayed as a heat map to allow users to see visually where most traffic incidents are ocuring.
The map display has more pastel tones, and the roadways are more bold so that the Traffic Incident Data stands out as it is the focal point of this Lab.
The map is published and the access token and link to the tile layer are integrated into the code.
The MapBox website was used for its tutorials, on how to integrate the tile layer in HTML: https://docs.mapbox.com/mapbox.js/example/v1.0.0/stylelayer/

The toggle feature on the top right of the map allows users to switch between a 'regular' map and the heatmap of the traffic incidents dataset.
The building permit search still works on bith the regular map and the heatmap.
