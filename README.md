NAIP_WMS
========

These files were created from the links accesible here: https://gis.apfo.usda.gov/arcgis/rest/services/NAIP/USDA_CONUS_PRIME/ImageServer

These are WMS services for the current NAIP (National Agriculture Inventory Program). These files span the years from 2012 to 2015. They are flown Leaf on usually from late spring to late summer. 

As more years become available I will be updating these files. 


Usage
========
These files were create to be loaded into QGIS. Tested on 3.4 and 3.10 

1. Open QGIS 3.x 
2. Open the Data Source Manager. 
3. Open the WMS/WMTS section. Click Load and select the XML you wish to load. Load NAIP_Imagery_38.xml for any version of QGIS greater than 3.0 and less than 3.10. Load NAIP_Imagery_310.xml for QGIS 3.10.  
4. Select the connection to import 
5. Connect

Dates of NAIP. 
Map Server Connection: https://gis.apfo.usda.gov/arcgis/rest/services/NAIP/NAIP_Image_Dates/MapServer

1. Open QGI3.x 
2. Open the Data Source Manager. 
3. Open the ArcGIS Map Server and define a New Connect and copy the above connection into the URL text box. 
4. Connect. Select the state or the year to see the metadata on the date captured. 

Warning
========
* The assumption is you will have the internet for these files to work. Granted I don't always have the internet so you might need to download the individual files by US County from http://datagateway.nrcs.usda.gov/
* In the case of Government Shutdown these links will not work (which is so unbelievably stupid I hate even typing that). 
* There is a chance I don't have some of the links working properly - if so contact me (or correct and I'll merge your changes back in). 


I just want to tell you Good Luck. We're All counting on you!
