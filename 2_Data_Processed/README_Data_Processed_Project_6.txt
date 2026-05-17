README FOR PROCESSED DATA - PROJECT 6

Project Title:
Drought and Vegetation Stress Mapping in Kenya Using CHIRPS Rainfall and Sentinel-2 NDVI

Prepared by:
Vivian Mbachi

Folder:
2_Data_Processed

Purpose of this folder:
This folder stores the processed raster outputs used for final ArcMap styling, map layout creation, and project interpretation.

Processed files included:

1. Drought_Stress_CHIRPS_NDVI_Kenya_2023.tif
Description:
Final combined drought stress priority raster for Kenya in 2023.
Created by combining CHIRPS rainfall classes and Sentinel-2 NDVI vegetation stress classes.

2. Precipitation_CHIRPS_Class_Kenya_2023.tif
Description:
Processed CHIRPS rainfall class raster for Kenya in 2023.
Created by summing daily CHIRPS rainfall for 2023 and classifying the annual rainfall into five rainfall classes.

3. Vegetation_NDVI_Stress_Class_Kenya_2023.tif
Description:
Processed Sentinel-2 NDVI vegetation stress raster for Kenya in 2023.
Created by calculating NDVI from Sentinel-2 imagery and reclassifying the result into five vegetation condition classes.

Processing completed before saving here:
1. Data accessed in Google Earth Engine.
2. Kenya boundary applied for clipping and masking.
3. CHIRPS rainfall summarized for 2023.
4. Sentinel-2 imagery filtered for 2023.
5. NDVI calculated from Sentinel-2 Band 8 and Band 4.
6. Rainfall and NDVI rasters classified.
7. Combined drought stress priority raster created.
8. Final rasters exported as GeoTIFF files.
9. Rasters opened and styled in ArcMap.

Coordinate system:
WGS 84

EPSG Code:
EPSG:4326

Important note:
The files in this folder are the processed analysis rasters used for final mapping.
The original downloaded exports are also stored in 1_Data_Raw for backup and traceability.

Quality notes:
All three processed rasters opened successfully in ArcMap.
Value 0 was treated as background and hidden during map styling.
The rasters were used to create the final project maps in 5_Maps.