# Notes collected learning about spatialite etc.


## example shape files

import into db via gui

qgis to modify shapefile coord (crs) system to wgs84, that should match lat/longs from iphone etc. (i think?, e.g. unproven)

SELECT * FROM test where within(geomfromtext('POINT(174.88239 -41.06195)'), (test.geometry))

### SRID

Guess SRID from .prj file - normally with shapefile

lots of NZ gis data using SRID 27200 - 

* https://epsg.io/27200
* https://spatialreference.org/ref/epsg/nzgd49-new-zealand-map-grid/

## Java


## Links

* Docs - https://www.gaia-gis.it/gaia-sins/spatialite_topics.html
* Cookbook - https://www.gaia-gis.it/fossil/libspatialite/wiki?name=misc-docs
* Tutorial - https://www.gaia-gis.it/spatialite-1.0a/SpatiaLite-tutorial.html#t2.1
* What is spatialite - https://www.bostongis.com/PrinterFriendly.aspx?content_name=spatialite_tut01
* Point in polygon 
  * http://blog.crazystyle.net/2014/06/10/spatialite-find-if-point-is-in-polygon/
  * https://gis.stackexchange.com/questions/159366/help-finding-point-in-polygon-via-spatialite-with-example-karst-zones-data
* Network routing - https://www.gaia-gis.it/spatialite-2.3.0/spatialite-network-2.3.0.html
* Java
  * jdbc - https://www.gaia-gis.it/spatialite-2.4.0-4/splite-jdbc.html
 
### NZ linz data 

* https://data.linz.govt.nz/layer/88139-porirua-0075m-urban-aerial-photos-2016/
