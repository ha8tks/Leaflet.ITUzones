# Leaflet.ITUzones
### What is this?
Draw a ITU zones lines and labels.
>*ITU zone is a division of the entire earth's surface into a total of 90 zones , which is used in amateur radio .*
### Demo anyone?
[Have a look](https://ha8tks.github.io/Leaflet.ITUzones/examples/)
### Usage example
Include the Leaflet.VectorGrid, text-images, ituzones javasript file:
```bash
<script src="https://unpkg.com/leaflet.vectorgrid@latest/dist/Leaflet.VectorGrid.js"></script>
<script src="https://cdn.jsdelivr.net/npm/text-image/dist/text-image.js"></script>
<script src="https://ha8tks.github.io/Leaflet.ITUzones/src/L.ITUzones.js"></script>
```
After instantiating the map:
```bash
L.ITUzones({
	color : 'rgba(0, 0, 255, 0.6)'
}).addTo(map);
```
### Options
- **color**: The color of the lines and labels. Default `rgba(0, 0, 255, 0.6)` 
