DATASET METADATA README

Dataset Name:
CHIRPS Annual Rainfall for Kenya 2023

File Name:
Precipitation_CHIRPS_Kenya_2023

Data Type:
Raster climate dataset / precipitation image

What is this dataset?
This dataset represents annual rainfall across Kenya for the year 2023. It was created by summing daily CHIRPS precipitation images in Google Earth Engine.

Where was it downloaded or accessed from?
Website name:
Google Earth Engine Data Catalog / CHIRPS Daily Precipitation

Exact URL:
https://developers.google.com/earth-engine/datasets/catalog/UCSB-CHG_CHIRPS_DAILY

Earth Engine Dataset ID:
UCSB-CHG/CHIRPS/DAILY

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
precipitation

What does each band or column mean?
The precipitation band represents rainfall amount in millimeters.

Known limitations:
CHIRPS is a gridded rainfall estimate, not direct rainfall station measurement everywhere.
The spatial resolution is suitable for national and regional rainfall analysis, but not for very small local site-level rainfall decisions.
Rainfall values are estimates and may have uncertainty in areas with fewer ground stations.

Processing done:
Daily CHIRPS rainfall images from 2023-01-01 to 2023-12-31 were filtered in Google Earth Engine.
The daily images were summed to create annual rainfall for 2023.
The annual rainfall image was clipped to the Kenya boundary.
The raster was displayed using a rainfall color palette.

Output file created from this dataset:
No exported file yet. The rainfall raster was displayed in Google Earth Engine.

Quality notes:
The CHIRPS rainfall layer loaded successfully.
The annual rainfall raster displayed correctly over Kenya.
The Console error caused by printing the full CHIRPS collection was fixed by printing the dataset ID and image count instead.

Prepared by:
Vivian Mbachi

Project:
Project 6 - Drought and Vegetation Stress Mapping in Kenya