# MapboxJS_TurfJS_Test

__*Which prompt did you attempt?*__

Custom. Messing around with some points from our production data (scrubbed to be generic), and school data from the county. Attempt is to create concave polygons for each company and then do something like figure out which schools fall in which "territories".

__*What turf modules did you use?*__

featurecollection
concave

__*What was helpful about the documentation?*__

Well organized in general. 

__*What was not great about the documentation?*__

Some entries need a little more info. 

__*How can we improve it?*__

I wasn't particularly clear on how results were being added to the map. API-dependent I assume, but I'd still like to see it. Maybe just add a comment like, "add results to map (leaflet-specific)"
It took me quite awhile to figure out why I was getting polygons AND markers showing up when I added the concave hulls to the display (concat operation).
Ellaborate on examples. I like to see both a bare minimum example AND a more complex one. Bare min to get things rolling, complex, because reality.
Add a title for the geoJSON to make it clear it's the results ala
MAP DISPLAY
"geoJSON Results"
GEOJSON DISPLAY

__*What other resources did you use for help?*__

mapbox.js docs, stackexchange, other general search results
