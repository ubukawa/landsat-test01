# landsat-test01
Making raster tile from Landsat 8.  
This is for testing purpose.

# Source info
* Landsat 8 imagery from U.S.G.S.
* Spatial Resolution: 30 meter
* Processing level: L2SP (Surface reflectance)
* Scene Path and Row: 107-035 (around Tokyo, see WRS2 for detail)
* Obtained date: 2021-12-28
* Scene center time: 01:16

# Raster tile info
Color combination is the true colore (B4 B3, B2).
The above data values were streached and exported into 24bit RGB image file so that the color can be seen easily.
Then, it is exported as raster tile (ZL6-12, tileSize 256).  

https://ubukawa.github.io/landsat-test01/test-image01/default/{z}/{x}/{y}.png   

# map (mapbox gl js ver. 1)
https://ubukawa.github.io/landsat-test01/test-image01/test-map.html  
https://ubukawa.github.io/landsat-test01/test-image01/test-simple.json

# map (leaflet)
https://ubukawa.github.io/landsat-test01/test-image01/default/map-def.html

# Copyright of the Landsat 8 Imagery
Landsat-8 image courtesy of the U.S. Geological Survey  
https://www.usgs.gov/centers/eros/data-citation
