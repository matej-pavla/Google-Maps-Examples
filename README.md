# Google-Maps-Examples

BoundariesExample
————————
In this example I demonstrate how can Google Maps API v3’s Data Layer be utilised to display boundaries. I load the boundaries using from GeoJson files (In this example I use World Countries and US States boundaries). If you need to display your own boundaries and you only have Shapefile / KML file available, you can use utilities like ‘mapshaper’ (https://github.com/mbloch/mapshaper) to convert them. For example: 
```
mapshaper -i provinces.shp -o format=geojson world..json
```