# PopGrid-SDG11.5-Tutorial
Tutorial to use Popgrid estimates for Earthquake hazards and exposed population

The Colab link has more details of the essential libraries for installation and Tutorial explination
https://colab.research.google.com/drive/1GZ0dOCsn0jNkA96tDD9teOVyVemWQGfW?usp=sharing

Cliping Step for Raster Based on Imported Country Shapefile
Authored By Cascade Tuholske, Sep 2020
Updated By Hazem Mahmoud, Sep 2021
Notebook to clip rasters.
NOTE Available to be run for all geographies: Egypt for EGY.shp, nepal.shp for Nepal, chile.shp for chile
Download your target country shapefile from https://gadm.org/
Download your target shakemap from https://earthquake.usgs.gov/data/shakemap/
General Workflow
1. import your country boundry in .shp file format
2. import your shake map from USGS .shp file format
3. locate your 2 files path and edit the path in the script
4. follow the steps in ascending order
     
     a. clip population _match.tif from country .shp to _match_country.tif
     b. clip urban & rural from country .shp to _match_urban_country.tif & _match_rural_country.tif
     c. deffrentiate between the exposed population to urban and rural using the shakemap .shp from USGS

**NOTE - THIS REPO IS A WORK IN PROGRESS.** - CPT Oct. 2021 
