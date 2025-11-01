# 🛰️ CORINE Hotspot Analysis

A reproducible workflow for identifying and analyzing subsidence hotspots in Great Britain using Earth Observation and Open Geospatial data.

---

## 📌 Project Goal

This repository supports the detection and interpretation of **land subsidence hotspots** using **EGMS vertical velocities**, combined with **land cover trajectories** (CORINE, MODIS, S2) and proximity to **road infrastructure**. The outputs are intended to inform climate-sensitive infrastructure risk assessments.

---

## 📂 What's Included

- 🔻 EGMS-based hotspot extraction and grid generation
- 🌍 CORINE Land Cover (2000–2018) sampling using Earth Engine
- 🛰️ MODIS + Sentinel-2 land cover classification (2001–2024)
- 🌱 NDVI, EVI, SAVI, and NDWI vegetation metrics (Landsat + Sentinel)
- 🚧 Road network intersection with subsidence hotspots (OpenRoads)
- 🗂️ GeoJSON/CSV exports of hotspot grids, points, road segments

---

## 🛠️ Requirements

Install these packages before running locally or in Colab:

```bash
earthengine-api
geopandas
pandas
shapely
folium


