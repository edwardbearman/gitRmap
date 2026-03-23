# gitRmap / "Guitar Map"

A semi-automated map of locations, which you can add your own points to. Designed for those who are new to GIS, but know a little bit of Git. 

## Quick Start:

- Go to https://github.com/nickbearman/gitRmap/
- **Fork**: Click Fork, Give your map a name, Click Create fork
- Setup **GitHub Pages** - Deploy from branch - main - docs/, Go to Actions. I understand my workflows, enable them. 
- **Edit** the file **data/locations.csv**, Make your changes, Click Commit Changes, A Brown dot - means it is running. 
- **Wait ~1min** for GitHub Actions to run
  - Click Actions - see 2 entries - update locations and pages build and deployment
  - Wait for them to complete. 
  - Update locations should take ~1min.  
  - Build pages and depolyment should take <1 min
  - Click build pages and depolyment
- When complete, **go to https://(username).github.io/gitRmap/ to see your map**

More detailed tutorial to follow. 

## FAQ:

*Frequently Asked Questions will go here*

## History:

This was inspired by Michele Tobias's Travelling GIS Chat Book map setup in 2023 (https://github.com/MicheleTobias/traveling-gis-chat-book) which is a automated Leaflet webmap, where users can provide locations (city, state, country) in a CSV file, and GitHub actions will create the Leaflet map using an R script.

In April 2025, I was at the [Open Science Retreat](https://open.science-retreat.org/) where I was asked to create a web map showing a series of points with some pop-up text. This is a simple map for a GIS user to create, but the people who were asking were not GIS users, but they did know Git. Instead of just creating the map for them, I wanted to give them the tools to create the map themselves. I tweaked the Travelling GIS Chat Book map for them to create the [Open Science Activism Map](https://nickbearman.com/open-science-activism-map/). 

This worked, but wasn't really complete and wasn't something people could pick up and use. In Dec 2025, I applied for £500 from [OSGeo:UK's GoFundGeo](https://uk.osgeo.org/gofundgeo.html) to make this happen, and this was funded. Thanks to OSGeo:UK!

![OSGeo:UK logo](https://github.com/tomchadwin/qgis2web/assets/89784373/275553ce-39bd-42b2-81d3-12e551ce1261)




<!-- 


****

To update the map, edit this file [[https://github.com/nickbearman/open-science-activism-map/edit/main/data/locations.csv]([https://github.com/nickbearman/gitRmap/blob/main/data/locations.csv] and submit a PR. The code needs to be pulled. Then some R has to run to create the map (Nick can do this, but it should be able to be automated). Then the map should update. 



## Contribute

The [Issues List](https://github.com/MicheleTobias/traveling-gis-chat-book/issues) is a good place to list ideas or report issues. It's also a good place to find out what the community wants to add or improve on the map, as well as have discussions about how to approach each task and let people know what you're working on.

New to Leaflet? Get an introduction to making a web map with Leaflet with DataLab's [Building Web Maps with Leaflet Workshop](https://ucdavisdatalab.github.io/workshop_web_maps/).

New to HTML? W3Schools has a great [tutorial and reference for HTML](https://www.w3schools.com/html/default.asp).

-->
