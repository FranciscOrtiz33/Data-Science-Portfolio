
# Data Science & Data Engineering Portfolio

Hi, I'm Francisco Javier Ortiz, a data professional with a background in Electronics and Telecommunications.

My work focuses on Python, data engineering, machine learning, and geospatial data processing. This portfolio showcases projects involving exploratory data analysis, data validation, database integration, and reproducible data workflows.

## Featured Projects

## Urban Earth Observation

**Geospatial Machine Learning · Remote Sensing · Google Earth Engine · Streamlit**

Interactive geospatial application for city-specific land-cover classification, multitemporal change detection, and Land Surface Temperature analysis.

The system trains a dedicated Random Forest model for each study area using Sentinel-2, spectral indices, SRTM, and ESA WorldCover reference labels. The trained classifier is reused for temporal inference, while Landsat 8/9 imagery is integrated to analyze surface temperature by predicted land-cover class.

### Highlights

- City-specific Random Forest models
- Sentinel-2 multispectral processing
- NDVI, NDBI, MNDWI, and BSI feature engineering
- SRTM elevation and slope integration
- Multiyear land-cover classification
- Land-cover transition matrices
- Gains and losses analysis
- Landsat Land Surface Temperature
- Integrated land-cover and thermal analysis
- Interactive Streamlit and Folium interface
- Google Earth Engine processing and GeoTIFF export

**Tech:** Python · Google Earth Engine · Streamlit · Folium · Pandas · Random Forest · Sentinel-2 · Landsat · SRTM · ESA WorldCover

[View Project](https://github.com/FranciscOrtiz33/urban-earth-observation)

### 1. Geospatial Data Validation & ETL Pipeline

**Python · Shapely · Pandas · Streamlit · PostgreSQL/PostGIS · Docker · QGIS**

A geospatial data processing application that validates agricultural lot geometries before loading them into a spatial database.

**Key features:**
- Validation of Polygon and MultiPolygon geometries.
- Detection of self-intersections, empty geometries, and unsupported geometry types.
- Export of valid and invalid records for review.
- GeoJSON export for visual inspection in QGIS.
- Approved data submission to PostgreSQL/PostGIS.
- Duplicate prevention and automated validation tests.

**[View project →](https://github.com/FranciscOrtiz33/geospatial-data-pipeline)**

### 2. Titanic — Exploratory Data Analysis

**Python · Pandas · Matplotlib · Jupyter Notebook**

Exploratory analysis of the Titanic passenger dataset, investigating the relationships between survival, sex, passenger class, and age.

**Key features:**
- Data exploration and missing-value analysis.
- Survival rate comparisons.
- Analysis of interactions between passenger characteristics.
- Data visualization and interpretation of findings.

**[View project →](https://github.com/FranciscOrtiz33/python-data-analysis)**

## Technical Skills

**Programming and data:** Python, SQL, Pandas, NumPy

**Databases and data engineering:** PostgreSQL, PostGIS, ETL, data validation, REST APIs

**Geospatial:** Shapely, GeoPandas, QGIS, Google Earth Engine

**Machine learning:** Scikit-learn, exploratory data analysis, model evaluation

**Tools:** Git, GitHub, Docker, Streamlit, Jupyter Notebook

## About This Portfolio

Projects are documented with their objectives, technologies, methodology, and limitations. The geospatial pipeline uses synthetic data and a standalone implementation suitable for public demonstration.
