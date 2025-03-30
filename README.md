# ***Leaflet-challenge***

# 🌍 Earthquake Visualization with Leaflet.js

# ***📌 Overview***

This project uses Leaflet.js, JavaScript, and GeoJSON data from the USGS (United States Geological Survey) to create an interactive web map that visualizes recent earthquake activity across the globe. The map dynamically displays the magnitude, depth, and location of each earthquake using color-coded and size-scaled markers.


# ***🧪 Data Source***

Earthquake data is fetched from the USGS GeoJSON Feed:

Example used: All Earthquakes from the Past 7 Days

This data is updated every 5 minutes and includes metadata like:

- Location (latitude, longitude)

- Magnitude

- Depth

- Time

- Place description


# ***🗺️ Features***

✅ Earthquake Map

- 📍 Markers placed on map by coordinates.

- 🔴 Marker size scales with magnitude of the earthquake.

- 🌈 Marker color represents depth (deeper = darker).

- 🪧 Popups display key information about each earthquake (location, magnitude, depth, time).

- 🧭 Legend included to explain depth-based coloring.

- 🌍 Tile Layer from Leaflet (OpenStreetMap) provides a base map.



# ***🧠 Logic Highlights***

- Marker size: radius = magnitude * scalingFactor

- Marker color: depth determines fill color using custom thresholds



# ***⚙️ Technologies Used***

- 🗺️ Leaflet.js – Interactive maps

- 📊 D3.js – Fetching and parsing GeoJSON

- 🌐 HTML/CSS/JavaScript

- 📡 GeoJSON – Real-time earthquake data

- 🔗 OpenStreetMap – Map tile provider
