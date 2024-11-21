When following:

https://switch2osm.org/serving-tiles/manually-building-a-tile-server-debian-12/

Use this version of project.mml file to enable english style names on map tiles.

This can be done on an existing setup by:

nano project.mml
paste the file
carto project.mml > mapnik.xml
service renderd restart

