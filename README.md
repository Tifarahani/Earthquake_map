# Earthquake_map
---
## Project overview

The purpose of this project is to gather earthquake GeoJSON data from the USGS API, create and explore interactive maps of earthquakes around the world.
The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

---
### Deliverable 1: Add Tectonic Plate Data


- In this Deliverable the tectonic plate data is added as a second layer group and tectonic plate data is added to the overlay object.The d3.json() callback is working and does the following :
  - The tectonic plate data is passed to the geoJSON() layer
  - The geoJSON() layer adds color and width to the tectonic plate lines
  - The tectonic layer group variable is added to the map
  - The earthquake data and tectonic plate data displayed on the map when the page loads
  
<p align="center">  
<img src="https://github.com/Tifarahani/Earthquake_map/blob/main/Resources/Images/Map_data_1.png"  width="70%" height="70%">
</p>
<p align="center">  
<i>Figure 1:Tectonic Plate Data</i>
</p>

<p align="center">  
<img src="https://github.com/Tifarahani/Earthquake_map/blob/main/Resources/Images/Map_data_4_Earthquake.png"  width="70%" height="70%">
</p>
<p align="center">  
<i>Figure 2: Dark eathquake map</i>
</p>

### Deliverable 2: Add Major Earthquake Data

- In second deliverable the major earthquake data is added as a third layer group and the major earthquake data is added to the overlay object.
- The d3.json() callback is working and does the following
  -Sets the color and diameter of each earthquake.
  - The major earthquake data is passed to the geoJSON() layer.
The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
The major earthquake layer group variable is added to the map
All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off (5 pt)


<p align="center">  
<img src="https://github.com/Tifarahani/Earthquake_map/blob/main/Resources/Images/Map_data_2.png"  width="70%" height="70%">
</p>
<p align="center">  
<i>Figure 3: Major Earthquake Data</i>
</p>

### Deliverable 3: Add an Additional Map
<p align="center">  
<img src="https://github.com/Tifarahani/Earthquake_map/blob/main/Resources/Images/Map_data_3.png"  width="70%" height="70%">
</p>
<p align="center">  
<i>Figure 4: Additional Map</i>
</p>

---

### Resources
- JavaScript
- Virtual Studio Code 
- HTML
- CSS
- Leaflet.js
- geoJSON 
- Data Sources: 
  - Real-time earthquake data from https://www.usgs.gov/natural-hazards/earthquake-hazards/data-tools
  - Tectonic plate data from https://github.com/fraxen/tectonicplates


