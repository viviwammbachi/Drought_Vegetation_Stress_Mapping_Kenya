DATASET METADATA README

Dataset Name:
Combined Drought Stress Priority for Kenya 2023

File Name:
Drought_Stress_CHIRPS_NDVI_Kenya_2023

Data Type:
Classified raster decision-support layer

What is this dataset?
This dataset represents drought stress priority areas in Kenya for 2023. It was created by combining CHIRPS rainfall classes and Sentinel-2 NDVI vegetation stress classes.

Where was it downloaded or accessed from?
Website name:
Google Earth Engine Data Catalog

Main Data Sources:
1. CHIRPS Daily Precipitation
2. Sentinel-2 Surface Reflectance Harmonized

Exact URLs:
https://developers.google.com/earth-engine/datasets/catalog/UCSB-CHG_CHIRPS_DAILY
https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED

Earth Engine Dataset IDs:
UCSB-CHG/CHIRPS/DAILY
COPERNICUS/S2_SR_HARMONIZED

Date downloaded or accessed:
15 May 2026

Study area covered:
Kenya

Coordinate system / CRS:
Name:
WGS 84

EPSG Code:
EPSG:4326

Datum:
WGS 84

Projection:
Geographic coordinate system

Bands or columns included:
Drought_Stress_Class

What does each band or column mean?
Drought_Stress_Class represents combined drought stress priority based on rainfall condition and vegetation health.

Class 1:
Very high drought stress priority

Class 2:
High drought stress priority

Class 3:
Moderate drought stress priority

Class 4:
Low drought stress priority

Class 5:
Very low drought stress priority

Known limitations:
This is a simplified drought stress indicator.
It combines rainfall and NDVI only.
It does not include population, livestock, crop production, soil moisture, groundwater, market prices, or field observations.
The drought stress classes should be interpreted as screening or early-warning information, not as final ground truth.
The thresholds are general and may not perfectly represent all ecological zones in Kenya.

Processing done:
CHIRPS daily rainfall images for 2023 were summed to create annual rainfall.
Annual rainfall was classified into five rainfall condition classes.
Sentinel-2 imagery for 2023 was filtered and used to calculate NDVI.
NDVI was classified into five vegetation stress classes.
Rainfall class and NDVI class values were added to create a combined score.
The combined score was reclassified into five drought stress priority classes.
The final raster was clipped and masked to the Kenya boundary.
The final layer was displayed with Kenya national and administrative boundaries.

Output file created from this dataset:
No exported file yet. The combined drought stress raster was displayed in Google Earth Engine.

Quality notes:
The combined drought stress layer displayed successfully inside Kenya.
The layer visually shows higher drought stress priority in red and orange areas.
Supporting rainfall and NDVI class layers were added but turned off by default.
The output is suitable for national and regional NGO-style drought screening.

Prepared by:
Vivian Mbachi

Project:
Project 6 - Drought and Vegetation Stress Mapping in Kenya