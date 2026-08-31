# gitRmap / "Guitar Map"

A semi-automated map of locations, which you can add your own points to. Designed for those who are new to GIS, but know a little bit of Git. [Check out the demo](https://nickbearman.com/gitRmap/). 

## Quick Start:

- Go to https://github.com/nickbearman/gitRmap/
- **Fork**: Click Fork, Give your map a name, Click Create fork
- Setup **GitHub Pages** 
  - Deploy from branch - main - set folder to docs/, 
  - Go to Actions, click I understand my workflows, enable them. 
- **Edit** the file **data/locations.csv** 
  - Make your changes, Click Commit Changes, a brown dot - means it is running, a green tick means it is complete.
- **Wait ~1min** for GitHub Actions to run
  - Click Actions - see 2 entries - update locations and pages build and deployment
  - Wait for them to complete. 
  - Update locations should take ~1min.  
  - Build pages and deployment should take <1 min.
- When complete, **go to https://(username).github.io/gitRmap/** to see your map. [Check out the demo](https://nickbearman.com/gitRmap/).

More detailed [tutorial](https://nickbearman.com/gitRmap-docs/) and [YouTube video](https://youtu.be/-N1I1okulN4) available. 

## FAQ:

How do I setup gitRmap?
 - Fork the repo at [https://github.com/nickbearman/gitRmap](https://github.com/nickbearman/gitRmap). Follow the instructions in the README.md file, or check out this [YouTube video](https://youtu.be/-N1I1okulN4).

How do I add a point?
  - Add a row to `locations.csv`. Add your City, State and Country in the relevant columns (State is not always required). You do **not** need to add the coordinates in `lat` and `long` - these will be added automatically. 

How do I edit the attribute data shown?
  - The attribute data shown in the popup (Name, Job, Contact etc.) is dynamically created based on the columns in `locations.csv`. The standard column are `city`, `state`, `country`, `lat` and `long`. If you have no other columns, there will be no popup. (Rename `locations-no-popup.csv` to `locations.csv` and see what happens). If you have extra columns, they will appear in the popup. The column named `contactlink` will be rendered as a HTML link. 

What if I don't want any popups?
  - Remove all the extra columns, so you only have `city`, `state`, `country`, `lat` and `long`. Then no popup will be created. 

How do I update to the latest version of gitRmap?
 - Updates will be made to the gitRmap repo at [https://github.com/nickbearman/gitRmap](https://github.com/nickbearman/gitRmap). Use **Sync Fork** in GitHub to get the updates to your repo. See this [YouTube video](https://www.youtube.com/watch?v=4L0VEnqRvwQ) for details. 

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
