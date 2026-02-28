# Wildfire Analysis: Tizi Ouzou (August 2021)
This project uses Google Earth Engine and geemap in Google Colab to analyze wildfire impact and vegetation health in Tizi Ouzou, Algeria during August 2021. 
# Project Overview
This project analyzes and classifies burned vs. unburned areas caused by the August 2021 wildfires in Tizi Ouzou, Algeria using satellite imagery and machine learning.
Using Sentinel-2 satellite data from the European Space Agency and Google Earth Engine, we compute multiple spectral indices and train a Random Forest classifier to automatically detect burned areas.

The result is an interactive map showing Burned vs Unburned Areas
![photo_5841572169207450960_w (2)](https://github.com/user-attachments/assets/7fe37414-7d18-4898-8667-0d5a4c0c8e4c)


# 🌍 Study Area
## 📍 Tizi Ouzou, Algeria
## Wildfire period: August 20 – September 10, 2021

#🛰️ Data Source
Satellite Imagery: European Space Agency Sentinel-2
Dataset: Google Earth Engine – COPERNICUS/S2_SR_HARMONIZED

# Spectral Indices Computed
To improve burn detection accuracy, multiple indices were calculated:
NBR – Normalized Burn Ratio (burn severity detection)
NDVI – Vegetation health
NDWI – Water/moisture detection
MSAVI – Soil-adjusted vegetation index
SWIR/NIR Ratio – Fire damage sensitivity
These indices enhance separability between burned and unburned surfaces.

#Machine Learning Model
Algorithm: Random Forest
100 trees
