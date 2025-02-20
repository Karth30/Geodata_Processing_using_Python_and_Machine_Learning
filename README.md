# Geodata_Processing_using_Python_and_Machine_Learning
To perform the Geospatial Analysis of Geospatial data using Python and Machine learning.

A Geospatial data is a geographically referenced data describing the location and characteristics of the spatial features.

Sources: Remote sensing, Photogrammetry, GNSS (Global Navigation Satellite System), ALTM (Airborne Laser Terrain Mapping), Hardcopy maps, etc. 

The geospatial technology enables the procurement of Location-specific data about the earth.

The Remote sensing comprises of the sensors operating at different EM frequency bands.

The Geographic Information System (GIS) is a computer system that enables the spatial data creation, updation, visualisation and analysis.

The satellite navigation gives the data of positioning, time (GPS, NavIC), etc.

The data should be spatial (size of data acquired on the ground), temporal (continuity of the data generated with time) and spectral (procured from different bands of frequencies).

The GIS offers Data capturing, preparation, management, analysis, visualisation, presentation and mainly, the integration.

The main problems faced are : spatio-temporal problems. These occur in cases of dynamic objects of study whose characteristics change in differnt location and the change is also temporal (varying with respect to time).

The computer representation  of Geodata is of two types:

1)Raster Data Model: It is a grid( area covered by equal sized cells-pixels) based data structure whose smallest element is a pixel (Eg:Satellite Images, Maps). Attributes are recorded by assigning each cell a single value based on the majority feature in the cell. Each pixel has a digital number(DN) representing Spectral Reflectance Value. Lesser the size of pixel, more will be information(also, depends on pixel depth-Radiometry) obtained and  less will be the area viewed (Elevation and temperature are good for continuous features). Techniques like Zonal, Neighborhood, Physical distance and Local operations are performed.
Formats - GeoTiff, NetCDF, HDF and IMG.

EPSG - European Petroleum Survey Group: they assign the coordinates.

2)Vector Data Model: It is a Geometry based data structure which has the elements of point, line and polygon (Eg:Boundaries, roads represented as lines).Attributes are referenced through unique ID numbers to tables(Property lines, poltical boundaries and transportation lines are good for dicrete boundary consisting features). Techniques like Overlay operation (common between maps are found and comparitive analysis is done for finding overlays) are performed. It can be used in Terrain analysis.
Formats - Shape files, WKT and GeoJSON.

![image](https://github.com/user-attachments/assets/450ec16b-233f-40c1-93f3-5b26169557db)

Open-source Datasets that can used:

![image](https://github.com/user-attachments/assets/4a5a1354-2eb2-49f7-8752-c80702a85f29)








