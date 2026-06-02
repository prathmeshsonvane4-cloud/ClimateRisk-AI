**# ClimateRisk-AI

Satellite-Based Flood Risk Assessment Platform using Sentinel-1 SAR and Google Earth Engine.

---

## Project 1: Assam Flood Mapping (June 2022)

This project maps flood extent in Assam using Sentinel-1 SAR imagery and Google Earth Engine.

### Methodology

- Sentinel-1 SAR VV polarization
- Before vs During flood change detection
- Speckle filtering
- Permanent water removal (JRC Global Surface Water)
- Terrain filtering using SRTM DEM
- Connected pixel filtering
- Raster to vector conversion

### Datasets

- Sentinel-1 SAR
- SRTM DEM
- JRC Global Surface Water

### Outputs

- Flood Extent GeoTIFF
- Flood Polygon GeoJSON
- Flood Area Estimation

### Results

Flood Area Detected: ~463 km²

### Tools Used

- Google Earth Engine
- JavaScript
- Sentinel-1 SAR
- GIS & Remote Sensing

---

## Repository Structure

code/
data/
images/
**
