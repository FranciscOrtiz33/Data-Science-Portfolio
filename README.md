# Data Science & Data Engineering Portfolio

Hi, I'm **Francisco Javier Ortiz**, a data professional with a background in Electronics and Telecommunications.

My work focuses on **Python, data engineering, machine learning, geospatial analytics, and remote sensing**. This portfolio showcases projects involving geospatial machine learning, ETL pipelines, data validation, database integration, exploratory data analysis, and reproducible data workflows.

---

## Featured Projects

### 1. Urban Earth Observation

**Geospatial Machine Learning · Remote Sensing · Google Earth Engine · Streamlit**

Interactive geospatial application for **city-specific land-cover classification, multitemporal change detection, and Land Surface Temperature analysis**.

The system trains a dedicated Random Forest model for each study area using Sentinel-2 multispectral imagery, spectral indices, SRTM topographic variables, and ESA WorldCover reference labels. The trained classifier is then reused for temporal inference, while Landsat 8/9 imagery is integrated to analyze surface temperature by predicted land-cover class.

**Key features:**

- City-specific Random Forest models.
- Sentinel-2 multispectral preprocessing.
- NDVI, NDBI, MNDWI, and BSI feature engineering.
- SRTM elevation and slope integration.
- ESA WorldCover-based reference labels.
- Multiyear land-cover classification.
- Land-cover area and trend analysis.
- Gains, losses, and transition matrices.
- Landsat 8/9 Land Surface Temperature analysis.
- Integrated land-cover and thermal change analysis.
- Interactive Streamlit and Folium interface.
- Google Earth Engine processing and GeoTIFF export.

**Tech:** Python · Google Earth Engine · Streamlit · Folium · Pandas · Random Forest · Sentinel-2 · Landsat 8/9 · SRTM · ESA WorldCover

[**View project →**](https://github.com/FranciscOrtiz33/urban-earth-observation)

---

### 2. Geospatial Data Validation & ETL Pipeline

**Python · Shapely · Pandas · Streamlit · PostgreSQL/PostGIS · Docker · QGIS**

A geospatial data-processing application that validates agricultural lot geometries before loading approved records into a spatial database.

The project reproduces a practical geospatial ETL workflow involving ingestion, geometry validation, quality control, review, database integration, and duplicate prevention.

**Key features:**

- Validation of Polygon and MultiPolygon geometries.
- Detection of self-intersections, empty geometries, insufficient coordinates, and unsupported geometry types.
- Separation of valid and invalid records.
- CSV and GeoJSON outputs for review.
- Visual inspection workflow using QGIS.
- PostgreSQL/PostGIS integration.
- Duplicate-record prevention.
- Automated validation workflow.
- Interactive Streamlit interface.

**Tech:** Python · Pandas · Shapely · PostgreSQL · PostGIS · Streamlit · Docker · QGIS · GeoJSON

[**View project →**](https://github.com/FranciscOrtiz33/geospatial-data-pipeline)

---

### 3. Titanic — Exploratory Data Analysis

**Python · Pandas · Matplotlib · Jupyter Notebook**

Exploratory analysis of the Titanic passenger dataset, investigating relationships between survival and passenger characteristics including sex, passenger class, and age.

The project focuses on data exploration, missing-value analysis, group comparisons, visualization, and interpretation of patterns in the dataset.

**Key features:**

- Dataset inspection and missing-value analysis.
- Survival-rate comparisons by sex.
- Survival analysis by passenger class.
- Age-group analysis.
- Interaction analysis between sex and passenger class.
- Data visualization and interpretation of findings.

**Tech:** Python · Pandas · Matplotlib · Jupyter Notebook

[**View project →**](https://github.com/FranciscOrtiz33/python-data-analysis)

---

## Technical Skills

**Programming & data analysis:**  
Python · SQL · Pandas · NumPy

**Data engineering:**  
ETL/ELT · Data validation · REST APIs · Data preprocessing · Reproducible workflows

**Databases:**  
PostgreSQL · PostGIS · Spatial SQL

**Geospatial & remote sensing:**  
GeoPandas · Shapely · QGIS · Google Earth Engine · Sentinel-2 · Landsat · SRTM · GeoJSON

**Machine learning:**  
Scikit-learn · Random Forest · Feature engineering · Model evaluation · Classification

**Visualization & applications:**  
Streamlit · Folium · Matplotlib · Jupyter Notebook

**Development tools:**  
Git · GitHub · Docker · VS Code · WSL

---

## About This Portfolio

The projects in this portfolio are designed to demonstrate practical skills across **data science, data engineering, machine learning, and geospatial analytics**.

Each repository documents its objectives, methodology, technologies, implementation, and limitations.

The projects range from exploratory data analysis to end-to-end applications involving geospatial processing, machine-learning models, database integration, quality-control workflows, remote sensing, and interactive visualization.

Where proprietary datasets or systems were involved in the original professional context, the public implementations use synthetic, open, or independently reproducible data and workflows.