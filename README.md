# map-pizzaOutlet
This project is a Pizza Outlets Map using Leaflet.js and OpenStreetMap. It displays various pizza outlets on an interactive map, allowing users to view their locations and details, and seamlessly zoom into specific outlets by clicking on the list or map markers.

# Features
Interactive Map: Displays pizza outlets on a map using OpenStreetMap tiles.<br>
Custom Markers: Each pizza outlet is marked with a custom pizza icon.<br>
Fly to Location: Click on any outlet from the list, and the map will zoom to its exact location.<br>
Popup Information: Clicking on a map marker or list item shows the outlet's details, including the name, address, and phone number.
Smooth Map Interaction: Provides a smooth flying effect to the store's location when selected from the list.

# Tech Stack
Leaflet.js: A lightweight, open-source JavaScript library for interactive maps.
OpenStreetMap: A free map tile provider for global mapping.
HTML/CSS/JavaScript: Front-end technologies for creating the interface and functionality.

Changing Map Settings: Modify the setView method in app.js to set a different default map view or zoom level:
const myMap = L.map('map').setView([latitude, longitude], zoomLevel);

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# ![Screenshot 2024-09-12 222308](https://github.com/user-attachments/assets/820820cf-31d2-47c7-acdb-7c8a9bb5534d)
Acknowledgments
Leaflet.js: Leaflet Documentation
OpenStreetMap: OpenStreetMap
Pizza Icon: Custom icon used to represent pizza outlets on the map.

