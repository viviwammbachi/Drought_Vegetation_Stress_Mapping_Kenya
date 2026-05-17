DATASET METADATA README

Dataset Name:
Kenya Administrative Boundaries - FAO GAUL 2015 Level 1

File Name:
Boundary_GAUL_Kenya_Admin1_2015

Data Type:
FeatureCollection / Administrative boundary

What is this dataset?
This dataset represents Kenya internal administrative boundaries from the FAO GAUL 2015 Level 1 dataset. It was used to show internal regional divisions within Kenya for drought and vegetation stress analysis.

Where was it downloaded or accessed from?
Website name:
Google Earth Engine Data Catalog

Exact URL:
https://developers.google.com/earth-engine/datasets/catalog/FAO_GAUL_2015_level1

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
ADM0_NAME:
Country name

ADM1_NAME:
Administrative unit name

What does each band or column mean?
ADM0_NAME identifies the country.
ADM1_NAME identifies the internal administrative unit.

Known limitations:
The FAO GAUL 2015 administrative boundary dataset may not fully match current Kenya county boundary datasets. It is useful for general analysis and study area display, but should not be used as the final legal county boundary dataset.

Processing done:
The FAO GAUL Level 1 dataset was filtered in Google Earth Engine where ADM0_NAME equals Kenya.
The boundaries were displayed as clean outline layers using ee.Image().byte().paint().

Output file created from this dataset:
No exported file yet. The administrative boundary layer was displayed in Google Earth Engine.

Quality notes:
The Kenya administrative boundaries loaded successfully.
The internal boundaries displayed correctly as thin gray lines.
The national boundary displayed correctly as a black outline.

Prepared by:
Vivian Mbachi

Project:
Project 6 - Drought and Vegetation Stress Mapping in Kenya