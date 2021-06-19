# Tree-Story-Cassini-Hackathon

This repository contains prototypes of the code which will be used to extract information from satellite data about individual trees.

Does_the_Tree_Exist!.inpy uses the gdal and rasterio libraries to read in 2018 Cyprus tree density data from the Copernicus Satellite. We reformat the input file so that it uses longitude and latitude coordinates and then write a function to transform any longitude and latitude coordinates to the pixels of the satellite image. Finally, we write a function which takes longitude and latitude as arguments and outputs whether or not the tree exists based on the tree density at that location, which is represented by a range of color values.  

QR code.inpy generates a QR code which is connected to the longitude and latitude of an individual tree.
