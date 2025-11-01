# corine-hotspot-analysis
Full geospatial data pipeline for hotspot monitoring (2000–2024) using Google Earth Engine. Includes land cover (CORINE, MODIS), vegetation indices (NDVI, EVI, SAVI), climate (TerraClimate), topography (DEM), proximity to water/urban, and roads in subsiding zones.

# 🌍 CORINE Hotspot Subsidence Analysis (2000–2024)

This repository contains a fully reproducible geospatial analysis pipeline for detecting and characterizing ground deformation hotspots across Europe. It combines Sentinel-1 vertical velocity data (EGMS), land cover (CORINE, MODIS), vegetation indices, topographic and climatic variables, and road infrastructure overlays.

## 📦 What's Inside

- **EGMS filtering**: Subsidence extraction from Sentinel-1
- **Hotspot detection**: Velocity-based grid clustering
- **LULC overlays**: CORINE (2000–2018), MODIS (2001–2024)
- **Vegetation indices**: NDVI, EVI, SAVI, MNDWI, NDWI
- **Climate analysis**: TerraClimate temperature & precipitation
- **Proximity metrics**: Distance to urban and water
- **Road risk layers**: Clipped road segments in subsiding zones
- **Interactive mapping**: Folium-based visualization

## 🔁 Reproducibility

All scripts are numbered and modular. Outputs are saved in `.csv` and `.geojson` formats. See the `/code/` folder for full pipelines, including extraction, filtering, visualization, and analysis.

## 📂 Data

Final datasets (hotspot points, roads, summaries) will be published via Zenodo and linked here.

## 🧪 Citation

If you use this pipeline or any output data, please cite this repository or the associated publication (TBD).

## 🛠️ Requirements

Python 3.9+  
Install dependencies:  
```bash
pip install -r requirements.txt

