# U.S.POP_2019
## United States of America Population estimates for 2019
>
This is a proportional symbol map of the United States of America.  Proportional symbol maps use the visual variable size to display the data.

The basemap for this application was obtained from [leaflet](https://leafletjs.com). For this application the spatial data was provided by Dr. Jonathan Sugg.  The [US Census Bureau Population Estimates](www.census.gov) was the original source for the population estimates for the year 2019.  The data file was a .csv file.  I used [GeoJSON.io](geojson.io). to convert and the data into GeoJSON format and then save the file so I could use it in Atom, a text and source code editor, which allows you to display the map.  [According to](arcgis.com) arcgis.com "GeoJSON is an open standard geospatial data interchange format that represents simple geographic features and their nonspatial attributes." 

The map message is to show the population estimates of each state in the U.S.  The proportional symbol method displays a symbol,in this case a circle, which gets bigger in proportion to the size of the population estimate per the state it is representing. I also added a mouseover function to this map which changes the color of the circle as you hover your mouse over it.
