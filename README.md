# Exploring Bike Lockers in King County Transit Stations

Interact with map [here](https://nobulnl.github.io/TileExperimentRepo/)

## Introduction
This map is an exploration of all of the transit stations in King County with bike lockers. I wanted to see despite our local governance wanting us all to move towards more sustainable transportation, how much our current infrastructure can support that ideal. This [map](https://nobulnl.github.io/TileExperimentRepo/) shows all of the transit stations in King County that have bike lockers. Bike lockers are simply containers in which riders of local transit can store their bikes securely to prevent theft and allow them to take a bus or train unencumbered by their bikes.

## Tileset #1
![tile1](/assets/map1.png)
Tileset 1 is simply a regular reference map of Seattle, Washington to Belleveue area in a grayscale theme used from Mapbox.gl 

## Tileset #2
![tile2](/assets/map2.png)
Tileset 2 is a tile layer that was created by downloading a geojson file from the King County GIS website that graphs all of the transit locations that have bike lockers on premesis. Because it was just the points loaded in from the geojson I was not concerned with the background map because as you will see in the next tileset I would lay this data over another background.

## Tileset #3
![tile3](/assets/map3.png)
Tileset 3 is the aforementioned version of the tileset that has the data that was previously imported from the King County GIS database geojson file. In this tile set the green points represent all of the transit stations with lockers and the map in the background is still using the mapbox.gl hosted grayscale theme. 

## Tileset #4
![tile4](/assets/map4.png)
The fourth and final tileset is one that I have created essentially from scratch. The data points on the map are still the ones from the King County GIS database regarding transit stations with bike lockers yet the map in the background is a theme that I created in mapbox.gl that was a pseudomercator projected map that I chose to have display local neighborhood names and transit lines to better illustrate my point. I chose the color scheme of green becasue of the theme around sustainability and I found that light green in combination of the font was fairly easy on the eyes.


This map, tilesets and final theme were created by Lawrence Nobuyoshi Lorbiecki. The first and third tilesets use the grayscale theme from mapbox.gl studio's theme selector. The data was gathered from the King County GIS database. 
