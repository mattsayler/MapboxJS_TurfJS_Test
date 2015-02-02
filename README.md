# MapboxJS_TurfJS_Test

__*Which prompt did you attempt?*__

Custom. Messing around with some points from our production data (scrubbed to be generic), and school data from the county. Attempt is to create concave polygons for each company and then do something like figure out which schools fall in which "territories". Got as far as making the concave polygons.

__*What turf modules did you use?*__

 - featurecollection
 - concave

__*What was helpful about the documentation?*__

Well organized in general. 

__*What was not great about the documentation?*__

Some entries need a little more info. 

__*How can we improve it?*__

I wasn't particularly clear on how results were being added to the map. API-dependent I assume, but I'd still like to see it. Maybe just add a comment like, "add results to map (leaflet-specific)"
It took me quite awhile to figure out why I was getting polygons AND markers showing up when I added the concave hulls to the display (concat operation).
Ellaborate on examples. I like to see both a bare minimum example AND a more complex one. Bare min to get things rolling, complex, because reality.
Add a title for the geoJSON to make it clear it's the results:

 - MAP DISPLAY
 - "geoJSON Results"
 - GEOJSON DISPLAY

__*What other resources did you use for help?*__

mapbox.js docs, leaflet docs, stackexchange, other general search results

__*Other Notes*__

I noticed some strange results for Company4 (green poly's in NW and SE of map). Looks like there is a small hole in the NW poly, and what looks like a zero-area hole in the SE poly. Best guess is this a result of there being essentially two populations of points for the same company. I was surprised the concave operation actually made two polygons for that one period. Although, I haven't dug into the geometry of it. Maybe it's not creating two, there are just some geometric anomallies that makes it look as if it were...

