# Intertidal Zone and Salt Marsh Mapping in Morecambe Bay using Google Earth Engine and Sentinel-2 🌊🛰️
### Olivia Brennan MSc Disseration at UCL

This repository contains Jupyter Notebooks which extract shorelines from Sentinel-2 satellite imagery taken from Google Earth Engine's cloud-based database, as well as generates polygons of saltmarsh extent.

## 📂 Contents

- `Shoreline_Extraction_Morecambe_Bay` - Jupyter notebook which links Sentinel-2 scenes over Morecambe Bay to tide gauge data and filters based on tidal state to extract shoreline polygons using NDWI thresholding
- `Salt_Marsh_delineation_Morecambe_Bay` - Jupyter notebook which clips a Sentinel-2 scene over Morecambe Bay based on a HAT shoreline & extracts saltmarsh polygons based on NDVI thresholding
- `'HEY'files` - Contain formatted Tide Guage data from the UK National Tide Gauge Network for the years 2017-2025, at Heysham
- `'formatted metadata' files` - Contain the formatted metadata from Sentienl-2 scenes over Morecambe Bay
  


## Running the Notebooks

### 1. Clone the Repository

```bash
git clone https://github.com/oliviabrennan/DISSERTATION_MorecambeBay.git
cd DISSERTATION_MorecambeBay
```

### 2. Set Up a Virtual Environment 

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```
### 3. Launch Jupyter

```bash
jupyter lab
```

Then open the notebook of interest
---




