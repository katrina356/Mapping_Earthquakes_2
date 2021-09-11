# Mapping_Earthquakes_2

## Overview
In module 13 "Mapping Earthquakes with JS & APIs" I utilized the Leaflet.js application to populate maps with GeoJSON earthquake data.  I developed 3 layers to the map, added popups with data points and changed the points to circles 

## Process

### Index File
The Index file contains html code that pulls in our various links and styles for the web page:
    
1) Formatting of obects within the web page is pulled in from style.css file
       `<link rel="stylesheet" type="text/css" href="static/css/style.css">`
2) Leaflet style link is pulled in
        `<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"`
        `integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="`
        `crossorigin=""/>`
3) D3 javascript is pulled in
        `<script src="https://d3js.org/d3.v5.min.js"></script>`
4) The javascript with all our code
        `<script type="text/javascript" src="static/js/challenge_logic.js"></script>`

### Challenge Logic File and Process

Using Mapbox we created the background maps with three different layers. We then retrieved the earthquake data using the D3.json method.  From there we created various functions that set the style for the data points (circles), the colors of the circle data points, the radius of the circles based on magnitude and then to add all of this to the map.  We then refactored these functions as needed for the datapoints of earthquake data, tectonic lines and major earthquakes.

![GrayScaleMap](Simple_Map/GrayScaleMap.png)




    

