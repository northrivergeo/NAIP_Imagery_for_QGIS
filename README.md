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
3. Open the WMS/WMTS section. Load the naip_imagery_wms_connection.xml file.   
4. Select the connection to import 
5. Connect

ArcGIS Server Connection
========
1. Open QGIS 3.x 
2. Open the Data Source Manager. 
3. Open the ArcGIS Rest Server section. Load the naip_imagery_arcgisserver_connection.xml file.   
4. Select the connection to import 
5. Connect


Warning
========
* The assumption is you will have the internet for these files to work. Granted I don't always have the internet so you might need to download the individual files by US County from http://datagateway.nrcs.usda.gov/
* In the case of Government Shutdown these links will not work (which is so unbelievably stupid I hate even typing that). 


I just want to tell you Good Luck. We're All counting on you!
