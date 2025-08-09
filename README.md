# Intertidal Zone and Salt Marsh Mapping in Morecambe Bay using Google Earth Engine and Sentinel-2 🌊🛰️
### Olivia Brennan MSc Disseration at UCL

This repository contains Jupyter Notebooks which extract shorelines from Sentinel-2 satellite imagery taken from Google Earth Engine's cloud-based database, as well as generates polygons of saltmarsh extent.

## 📂 Contents

- `notebooks` — One to extract shorelines using NDWI and one to delineate salt marsh extent using NDVI
- `data` — Tide Guage data from the UK National Tide Gauge Network
- `figures` — Visualizations and maps from the project

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

Then open the notebook of interest (e.g., `notebooks/intertidal_analysis.ipynb`).

---




