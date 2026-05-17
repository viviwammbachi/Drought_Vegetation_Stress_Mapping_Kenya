DATASET METADATA README

Dataset Name:
Sentinel-2 NDVI for Kenya 2023

File Name:
Vegetation_NDVI_Sentinel2_Kenya_2023

Data Type:
Raster remote sensing dataset / vegetation index image

What is this dataset?
This dataset represents vegetation health across Kenya for the year 2023. It was created from Sentinel-2 Surface Reflectance imagery using the Normalized Difference Vegetation Index, also called NDVI.

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
NDVI_2023

What does each band or column mean?
NDVI_2023 represents vegetation condition calculated from Sentinel-2 imagery.
NDVI values usually range from -1 to +1.
Low or negative values may represent water, bare soil, built-up areas, or very sparse vegetation.
Higher positive values usually represent healthier or denser vegetation.

Known limitations:
The NDVI image is based on a median composite for 2023.
Cloud cover was reduced by filtering images with less than 20 percent cloud cover, but some cloud or atmospheric effects may still remain.
NDVI shows vegetation greenness, but it does not directly measure crop yield, food security, or drought impact by itself.
Seasonal variation can affect NDVI, so interpretation should consider rainfall seasons and local climate conditions.

Processing done:
Sentinel-2 Surface Reflectance Harmonized imagery was accessed in Google Earth Engine.
Images were filtered to the Kenya boundary.
Images were filtered from 2023-01-01 to 2023-12-31.
Images with CLOUDY_PIXEL_PERCENTAGE less than 20 were selected.
A median composite was created.
NDVI was calculated using Sentinel-2 Band 8 and Band 4.
The NDVI raster was clipped to the Kenya boundary.
The NDVI layer was displayed using a vegetation color palette.

Output file created from this dataset:
No exported file yet. The NDVI raster was displayed in Google Earth Engine.

Quality notes:
The Sentinel-2 image collection loaded successfully.
The NDVI raster displayed over Kenya.
Kenya national and administrative boundaries displayed above the NDVI layer.
The number of Sentinel-2 images used was printed in the Console.

Prepared by:
Vivian Mbachi

Project:
Project 6 - Drought and Vegetation Stress Mapping in Kenya