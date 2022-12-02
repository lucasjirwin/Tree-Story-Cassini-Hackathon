# Tree-Story-Cassini-Hackathon

This repository contains prototypes of the code which will be used to extract information from satellite data about individual trees.

<b> Does_the_Tree_Exist!.ipynb </b> uses the gdal and rasterio libraries to read in 2018 Cyprus tree density data from the Copernicus Satellite. We reformat the input file so that it uses standard longitude and latitude coordinates and then write a function to transform any longitude and latitude coordinates to the pixels of the satellite image. Finally, we write a function which takes longitude and latitude as inputs and outputs whether or not the tree exists based on the tree density at that location, which is represented by a range of color values. We confirm our results by using the SNAP ESA general user interface which we downloaded. 

<b> Carbon_Monoxide_Levels.ipynb </b> follows the same procedure as Does_the_Tree_Exist!.ipynb but outputs the Carbon Monoxide levels at the specific latitude and longitude of the tree. 

<b> QR code.ipynb </b> generates a QR code which is connected to the mockup of the Tree Story webpage of an individual tree. 
