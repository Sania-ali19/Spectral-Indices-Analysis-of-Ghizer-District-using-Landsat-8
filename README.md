**Spectral Indices Analysis of Ghizer District using Landsat-8**
📌 Overview

This project focuses on analyzing land surface characteristics of Ghizer District, Gilgit-Baltistan (Pakistan) using Landsat-8 satellite imagery. Multiple spectral indices were calculated to assess vegetation health, water presence, built-up areas, and bare land conditions. The analysis supports environmental monitoring, land use planning, and GIS-based decision making.

🗂️ Study Area

Region: Ghizer District, Gilgit-Baltistan

Boundary Data: Ghizer District Shapefile

Coordinate System: UTM / WGS 84 (as per dataset)

🛰️ Dataset Used

Satellite: Landsat-8 OLI

Source: USGS EarthExplorer

Bands Used:

Band 3 (Green)

Band 4 (Red)

Band 5 (Near Infrared – NIR)

Band 6 (Shortwave Infrared – SWIR)

📊 Spectral Indices Calculated

The following indices were generated using Raster Calculator after clipping all bands to the Ghizer District boundary:

1️⃣ NDVI (Normalized Difference Vegetation Index)
NDVI = (NIR - Red) / (NIR + Red)

Used to analyze vegetation density and health

2️⃣ NDWI (Normalized Difference Water Index)
NDWI = (Green - NIR) / (Green + NIR)

Used to identify water bodies

3️⃣ NDBI (Normalized Difference Built-up Index)
NDBI = (SWIR - NIR) / (SWIR + NIR)

Used to detect built-up areas

4️⃣ BSI (Bare Soil Index)
BSI = ((SWIR + Red) - (NIR + Blue)) / ((SWIR + Red) + (NIR + Blue))

Used to identify bare land and soil exposure

🛠️ Methodology / Workflow

Downloaded Landsat-8 imagery

Performed band stacking (if required)

Clipped all required bands using Ghizer District shapefile

Calculated spectral indices using Raster Calculator

Classified and symbolized results

Created final maps with proper layout elements

🗺️ Final Outputs

NDVI Map

NDWI Map

NDBI Map

BSI Map

Combined map layout for visualization

Each map includes:

Title

Legend

North Arrow

Scale Bar

💻 Software & Tools

ArcGIS / ArcMap

QGIS (optional)

USGS EarthExplorer

🎯 Applications

Vegetation monitoring

Water resource assessment

Urban expansion analysis

Environmental and land use studies

📌 Author

Sania Ali
GIS & Remote Sensing | Data Science Enthusiast

🔖 Tags

GIS RemoteSensing Landsat8 SpectralIndices NDVI NDWI GhizerDistrict
