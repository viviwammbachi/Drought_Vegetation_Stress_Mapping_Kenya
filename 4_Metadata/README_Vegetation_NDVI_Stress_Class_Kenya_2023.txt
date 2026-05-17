DATASET METADATA README

Dataset Name:
NDVI Vegetation Stress Classes for Kenya 2023

File Name:
Vegetation_NDVI_Stress_Class_Kenya_2023

Data Type:
Classified raster remote sensing dataset

What is this dataset?
This dataset represents vegetation stress classes across Kenya for 2023. It was created by reclassifying Sentinel-2 NDVI values into five easy-to-understand vegetation condition classes.

Where was it downloaded or accessed from?
Website name:
Google Earth Engine Data Catalog / Sentinel-2 Surface Reflectance Harmonized

Exact URL:
https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED

Earth Engine Dataset ID:
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
NDVI_Stress_Class

What does each band or column mean?
NDVI_Stress_Class represents reclassified vegetation condition.

Class 1:
Very low vegetation / severe stress

Class 2:
Low vegetation / moderate stress

Class 3:
Moderate vegetation

Class 4:
Healthy vegetation

Class 5:
Very healthy vegetation

Known limitations:
The classification is based on general NDVI thresholds and may not perfectly represent local vegetation conditions in every ecological zone.
NDVI can be affected by season, clouds, atmosphere, soil brightness, water, and land cover type.
This layer shows vegetation greenness, not direct crop yield or food insecurity.

Processing done:
Sentinel-2 imagery was filtered to Kenya for 2023.
Images with less than 20 percent cloud cover were selected.
A median composite was created.
NDVI was calculated using Band 8 and Band 4.
NDVI values were reclassified into five vegetation stress classes.
The classified raster was clipped and masked to the Kenya boundary.
The layer was displayed in Google Earth Engine with Kenya national and administrative boundaries.

Output file created from this dataset:
No exported file yet. The classified NDVI vegetation stress raster was displayed in Google Earth Engine.

Quality notes:
The first classified NDVI display showed color outside Kenya.
This was corrected using clipping and masking.
The final classified NDVI layer displayed only inside Kenya.
The layer is suitable for national and regional vegetation stress interpretation.

Prepared by:
Vivian Mbachi

Project:
Project 6 - Drought and Vegetation Stress Mapping in Kenya