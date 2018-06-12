<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8' />
    <title>Draw GeoJSON points</title>
    <meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />
    <script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.45.0/mapbox-gl.js'></script>
    <link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.45.0/mapbox-gl.css' rel='stylesheet' />
    <style>
        body { margin:0; padding:0; }
        #map { position:absolute; top:0; bottom:0; width:100%; }
    </style>
</head>
<body>

<div class="sqs-block code-block sqs-block-code" data-block-type="23" id="block-yui_3_10_1_1_1400852221439_13171"><div class="sqs-block-content"><iframe width='100%' height='500px' frameBorder='0' src='http://a.tiles.mapbox.com/v3/cgoranson.iadfb7eb/attribution,zoompan,zoomwheel,share.html'></iframe></div></div><div class="sqs-block html-block sqs-block-html" data-block-type="2" id="block-yui_3_17_2_1_1405211578765_20562"></div>

<div id='map' style='width: 400px; height: 300px;'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1IjoiY2dvcmFuc29uIiwiYSI6IkNJM1JQYkkifQ.yI-brVAu--FgYPYi50ua0g';
var map = new mapboxgl.Map({
container: 'map',
style: 'mapbox://styles/mapbox/streets-v10'
});
</script>
</body>
</html>
