
<html>
<head>
<meta charset="utf-8">
<title>Display a satellite map on a webpage</title>
<meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no">
<link href="https://api.mapbox.com/mapbox-gl-js/v2.7.0/mapbox-gl.css" rel="stylesheet">
<script src="https://api.mapbox.com/mapbox-gl-js/v2.7.0/mapbox-gl.js"></script>
<style>
body { margin: 0; padding: 0; }
#map { position: absolute; top: 0; bottom: 0; width: 100%; }
</style>
</head>
<body>
<div id="map"></div>
<script>
	mapboxgl.accessToken = 'pk.eyJ1IjoiZ3VycHJlZXRhY2hpbnQiLCJhIjoiY2wwMTl0ZjhzMDI2YzNscGEybXQ2MnNvbiJ9.aNZsNi-jXP_wVCH47oNXzQ';
const map = new mapboxgl.Map({
container: 'map', // container ID
style: 'mapbox://styles/gurpreetachint/cl01af2aj004v15po09nztlnd', // style URL
center: [137.9150899566626, 36.25956997955441], // starting position [lng, lat]
zoom: 9 // starting zoom
});
</script>
 
</body>
</html>
