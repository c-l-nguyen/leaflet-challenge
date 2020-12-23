# leaflet-challenge
A visualization of [USGS earthquake data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) using the Leaflet.js library. The data pulled were all the earthquakes from the past 7 days. The visualization tool used to create this map is Leaflet combined with the [Mapbox API](https://www.mapbox.com/). Various map skins were used as potential layers in this visualization. The map is located at https://c-l-nguyen.github.io/leaflet-challenge/. 

This map contains the locations of recent earthquakes around the world as well as their magnitude as indicated by the bubble size/color. A pop up window will appear if the user clicks on a bubble and return more information about the earthquake. A [tectonic plate layer](https://github.com/fraxen/tectonicplates) was also added to the map to show how close most earthquakes are to the earth's tectonic plates. The earthquake layer is always kept on top of the tectonic plate layer (resource to accomplish this is [here](https://gis.stackexchange.com/questions/183914/how-to-keep-vector-layer-on-top-of-all-layers-despite-toggling-order)).

Sample images of visualizations with different map layers:

## Satellite Map
![satellite-map](static/img/satellite_image.png)

## Light Map
![light-map](static/img/light_image.png)

## Outdoors Map
![outdoors-map](static/img/outdoors_image.png)