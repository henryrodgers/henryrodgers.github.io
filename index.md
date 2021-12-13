## Welcome to Our Website!

This website is the front-end of the Special Topics Data Visualization project, which can be found here: [https://github.com/nicoleyang14/special-topics](https://github.com/nicoleyang14/special-topics)

Thank you for your interest in our project. At this time, it is in the early stages of development. Please return later for more information!

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

<h2>Table Visualization Test</h2>
<table>
  <tr>
    <th>C1</th>
    <th>C1</th>
  </tr>
  <tr>
    <td>Publisher</td>
    <td>Centers for Disease Control and Prevention</td>
  </tr>
  <tr>
    <td>Contact Name</td>
    <td>Surveillance Review and Response Group</td>
  </tr>
  <tr>
    <td>Contact Email</td>
    <td>eocevent394@cdc.gov</td>
  </tr>
  <tr>
    <td>Bureau Code</td>
    <td>Centers for Disease Control and Prevention (009:20)</td>
  </tr>
  <tr>
    <td>Program Code</td>
    <td>Program Management (009:020)</td>
  </tr>
  <tr>
    <td>Public Access Level</td>
    <td>Public (public)</td>
  </tr>
  <tr>
    <td>Geographic Coverage</td>
    <td>US</td>
  </tr>
  <tr>
    <td>Theme</td>
    <td>Case Surveillance</td>
  </tr>
  <tr>
    <td>Update Frequency</td>
    <td>Twice Daily</td>
  </tr>
  <tr>
    <td>Temporal Applicability</td>
    <td>2020-01-21/..</td>
  </tr>
  <tr>
    <td>Homepage</td>
    <td>https://data.cdc.gov/d/9mfq-cb36</td>
  </tr>
  <tr>
    <td>Issued</td>
    <td>2020-06-11</td>
  </tr>
  <tr>
    <td>License</td>
    <td>https://www.usa.gov/government-works</td>
  </tr>
  <tr>
    <td>Last Update</td>
    <td>2021-12-11</td>
  </tr>
  <tr>
    <td>Unique Identifier</td>
    <td>https://data.cdc.gov/api/views/9mfq-cb36</td>
  </tr>
</table>