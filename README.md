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

## History:

To update the map, edit this file [[https://github.com/nickbearman/open-science-activism-map/edit/main/data/locations.csv]([https://github.com/nickbearman/gitRmap/blob/main/data/locations.csv] and submit a PR. The code needs to be pulled. Then some R has to run to create the map (Nick can do this, but it should be able to be automated). Then the map should update. 


, forked from https://micheletobias.github.io/traveling-gis-chat-book/, using R and Leaflet. 


<!-- 

# The Fellowship of the Traveling #GISChat Book
A web map of where the Traveling GIS Chat Book has been: https://micheletobias.github.io/traveling-gis-chat-book/

## Contribute

The [Issues List](https://github.com/MicheleTobias/traveling-gis-chat-book/issues) is a good place to list ideas or report issues. It's also a good place to find out what the community wants to add or improve on the map, as well as have discussions about how to approach each task and let people know what you're working on.

New to Leaflet? Get an introduction to making a web map with Leaflet with DataLab's [Building Web Maps with Leaflet Workshop](https://ucdavisdatalab.github.io/workshop_web_maps/).

New to HTML? W3Schools has a great [tutorial and reference for HTML](https://www.w3schools.com/html/default.asp).


## Updating the Map's Locations

As the book travels to new locations, this web map can be updated by adding new locations to the dataset.

Edit the `locations.csv` file, adding the city, state, and country information. **Leave the lat and long columns blank** if you don't have the lat/longs handy. The GitHub action on this repository will automatically geocode any blank lat/long columns.

-->
