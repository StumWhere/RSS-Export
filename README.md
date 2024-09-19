# RSS-Export
This tool creates a Raster Soil Survey (RSS) database as a File Geodatabase with a gSSURGO template (relational database) and as a SSURGO Download Folder


This toolset is a three tools in one from the original ArcMap Desktop version, 1) Create RSS DB by Map; 2) Import Raster to RSS db; 3) Open Source Export

This tool imports the text files and the raster into the file geodatabase with relationship classes and indices defined. 

The raster is imported and named MURASTER_10m_<State abbreviation>.

It then creates a SSURGO Download file structure with the tabular text files and exports the raster from the File Geodatabase as a GeoTIFF into the spatial directory.
