# corine-hotspot-analysis
Full geospatial data pipeline for hotspot monitoring (2000–2024) using Google Earth Engine. Includes land cover (CORINE, MODIS), vegetation indices (NDVI, EVI, SAVI), climate (TerraClimate), topography (DEM), proximity to water/urban, and roads in subsiding zones.

# CORINE Hotspot Analysis (2000–2024)

This repository contains the full geospatial analysis pipeline for monitoring environmental hotspots in Europe using Earth Observation data from 2000 to 2024.

## 🔍 Features

- Land cover change: CORINE & MODIS
- Vegetation indices: NDVI, EVI, SAVI, MNDWI, NDWI
- Terrain analysis: Elevation, Slope, Aspect (COPERNICUS DEM)
- Climate: Seasonal & annual precipitation + temperature (TerraClimate)
- Proximity metrics: Distance to water, urban
- Infrastructure: Roads intersecting with subsidence zones

## 📁 Data Outputs

All CSV and GeoJSON outputs are reproducible and structured for spatial modeling:
- `hotspot_points_with_coords.csv`
- `hotspots_MODIS_LULC_2001_2024.csv`
- `hotspots_S2_NDVI_DJF_2018.csv`
- `roads_in_subsidence_zones.geojson`
- And more…

## 💻 Reproducibility

All data extraction scripts are written in Python using the Google Earth Engine API.  
You can reproduce any dataset using the exact scripts included in this repository.

## 🧾 Citation

Please cite this repository or the companion paper if using the data or pipeline.

## 📜 License

See [LICENSE](./LICENSE) for usage rights.
