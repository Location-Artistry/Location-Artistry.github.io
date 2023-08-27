---
title: USGS Live Gage Data St. Joseph River 
date: 2021-09-16 01:00:00 -0400
categories: [locationVisualization,pastPost]
tags: [locationVisualization,discuss,leaflet,geoData,IoT,liveData,javascript,dataViz,observableHQ,widget,GeoJSON,API]
---
LocationVisualization post from September 2021.   
Query live data from USGS river gage sensors for St. Joseph River Basin Michigan.  Pull historical CSV data from additional USGS API and compare two source to generate current flow status.  Using leaflet map hover over station to show live status and current flow data.  Station color shows current status from Dark Blue/Green for high to Orange/Black for low.  Additional widget/cards for Median Gage Status from 13 stations, Summary table for all stations, and summary cards for mainstem stations.  All colorized for current flow conditions.   
Previously these calculations were developed as an API, and this example shows how the cross-comparison between these two APIs can be conducted entirely on the front end.    

    
[St. Joseph River USGS Gage Explorer](https://observablehq.com/@location-artistry/fork-of-st-joseph-river-usgs-gage-explorer)

<div id="observablehq-5c1daaa3"></div>
<p>Credit: <a href="https://observablehq.com/@location-artistry/fork-of-st-joseph-river-usgs-gage-explorer">St Joseph River USGS Gage Explorer by E. Kerney</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@location-artistry/fork-of-st-joseph-river-usgs-gage-explorer.js?v=3";
new Runtime().module(define, Inspector.into("#observablehq-5c1daaa3"));
</script>