# COG-Generator
Converts NetCDF files into COG (Cloud Optimized GeoTIFF) format 

A Cloud Optimized GeoTIFF (COG) is a regular GeoTIFF file, aimed at being hosted on a HTTP file server, with an internal organization that enables more efficient workflows on the cloud. It does this by leveraging the ability of clients issuing ​HTTP GET range requests to ask for just the parts of a file they need.

This notebook converts all the NC files in a folder, and converts them to COG format **using gdal-python on a notebook** and also has the instructions to make the conversion **using gdal on command window** .
