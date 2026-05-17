README FOR RAW GOOGLE EARTH ENGINE EXPORTS

Project:
Project 6 - Drought and Vegetation Stress Mapping in Kenya

Prepared by:
Vivian Mbachi

Folder:
1_Data_Raw

Purpose of this folder:
This folder stores the original GeoTIFF raster files exported from Google Earth Engine before any desktop GIS styling, processing, or map layout work.

Files included:

1. Vegetation_NDVI_Stress_Class_Kenya_2023.tif
Description:
Classified NDVI vegetation stress raster for Kenya in 2023.
Created from Sentinel-2 Surface Reflectance imagery in Google Earth Engine.
Classes represent vegetation condition from very low vegetation stress class to very healthy vegetation.

2. Precipitation_CHIRPS_Class_Kenya_2023.tif
Description:
Classified CHIRPS rainfall raster for Kenya in 2023.
Created by summing daily CHIRPS rainfall data for 2023 and classifying rainfall into rainfall condition classes.

3. Drought_Stress_CHIRPS_NDVI_Kenya_2023.tif
Description:
Combined drought stress priority raster for Kenya in 2023.
Created by combining classified CHIRPS rainfall and classified Sentinel-2 NDVI vegetation stress.

Original data sources:
1. Google Earth Engine
2. CHIRPS Daily Precipitation
3. Sentinel-2 Surface Reflectance Harmonized
4. FAO GAUL Kenya boundary

Export format:
GeoTIFF raster

Coordinate system:
WGS 84

EPSG code:
EPSG:4326

Export scale:
5000 meters

Date exported:
15 May 2026

Processing already completed in Google Earth Engine:
1. Kenya boundary loaded.
2. CHIRPS rainfall filtered to 2023.
3. CHIRPS daily rainfall summed into annual rainfall.
4. Rainfall classified into five classes.
5. Sentinel-2 imagery filtered to 2023.
6. Sentinel-2 imagery filtered by cloud cover below 20 percent.
7. NDVI calculated from Band 8 and Band 4.
8. NDVI classified into five vegetation stress classes.
9. Rainfall and NDVI classes combined into drought stress priority classes.
10. Final rasters clipped and masked to Kenya.
11. Final rasters exported to Google Drive as GeoTIFF files.

Important note:
These are raw exported analysis outputs from Google Earth Engine.
Any further desktop GIS styling, symbol changes, map layouts, or final map exports should be saved in the correct processed or maps folders.

Quality notes:
The files were confirmed in Google Drive under Project_6_GEE_Exports.
The files were downloaded and saved locally into 1_Data_Raw.