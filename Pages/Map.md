---
title: Map
layout: template
filename: Map.md
--- 

<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapquest example</title>
    <style>
      #map {
        width: 600px;
        height: 600px;
      }
    </style>
    <script src="https://api.mqcdn.com/sdk/mapquest-js/v1.3.2/mapquest.js"></script>
    <link type="text/css" rel="stylesheet" href="https://api.mqcdn.com/sdk/mapquest-js/v1.3.2/mapquest.css"/>
    <script>
      // 1. The basic part of the example
      var L;

      window.onload = function() {
        L.mapquest.key = 'Kkulaafxam9iXADKMFedCV9JsENBp7Yc';

        // 'map' refers to a <div> element with the ID map
        var map = L.mapquest.map('map', {
          center: [47.604325816529375, -122.1713779290056],
          layers: L.mapquest.tileLayer('map'),
          zoom: 12
        });
      }
    </script>
  </head>
  <body>
    <h2>Mapquest API Test</h2>

    <div id="map"></div>
  </body>
</html>