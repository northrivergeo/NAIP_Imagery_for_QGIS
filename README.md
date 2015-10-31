NAIP_WMS
========

These files were created from the links accesible here: http://gis.apfo.usda.gov/arcgis/rest/services/NAIP

These are WMS services for the current NAIP (National Agriculture Inventory Program). These files span the years from 2012 to 2015. They are flown Leaf on usually from late spring to late summer. 

As more years become available I will be updating these files. 


Usage
========
These files were create to be loaded into QGIS. Tested all the way through 2.12


1. Open QGIS 2.x 
2. Open the WMS/WTS Menu on the manage layers toolbar. 
3. Click Load and select the XML you wish to load. 
4. Select the connection to import 
5. Connect
6. Select PNG or JPEG or SVG for image encoding and not Tiff. Apparently tiff is showing a fourth band which appears to be alpha and is making the resulting connection look like a film negative. I'm working on figuring out if I can automatically change that somehow. 

Warning
========
* The assumption is you will have the internet for these files to work. Granted I don't always have the internet so you might need to download the individual files by US County from http://datagateway.nrcs.usda.gov/
* In the case of Government Shutdown these links will not work (which is so unbelievably stupid I hate even typing that). 
* There is a chance I don't have some of the links working properly - if so contact me (or correct and I'll merge your changes back in). 


I just want to tell you Good Luck. We're All counting on you!
