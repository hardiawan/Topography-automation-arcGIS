# Topography-automation-arcGIS
This code serves to help users to automate DTM Raster files to file Hillshade, Slope and Contour in ArcMap.


How to use this code :
1. Open a new, empty map document in ArcMap.
2. Click Geoprocessing >> Python.
3. Paste this code :

	execfile(r'*\topo_1.py')

4. Press enter, than follow the instructions
5. The process is automatically begin


This code has the flow: 
1. Hillshade
 a. Hillshade (.TIFF result)
2. Slope
 a. Slope
 b. Reclassify (to 7 classes based on Van Zuidam class classification)
 c. Raster to Polygon (.shp result)
3. Contour
 a. Contour
 b. Smooth Line (.shp result)

The results of the process will be placed in the "last_result" directory in the folder you previously selected
