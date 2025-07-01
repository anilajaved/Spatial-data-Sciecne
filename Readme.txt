# Japan Earthquake Geospatial Analysis Project

This project analyzes historical earthquake data in Japan using geospatial techniques to identify high-risk zones and visualize seismic activity patterns. The goal is to support earthquake risk awareness and disaster preparedness through data-driven insights.

---

## Project Objectives

- Analyze Japan’s earthquake history (2001–2018)
- Perform geospatial clustering of earthquake events
- Identify and visualize high-risk zones
- Generate statistical summaries by region
- Support disaster preparedness through visual tools

---

## Dataset

- **Source**: [Japan Meteorological Agency / USGS / Local Archives]
- **Period**: 2001 to 2018
- **Features**:
  - Latitude & Longitude
  - Magnitude
  - Depth
  - Date and Time
  - Region/Prefecture

---

## Tools & Technologies

- **Python**
- **Geopandas**: Spatial data manipulation
- **Matplotlib / Seaborn**: Visualization
- **Shapely**: Geometry operations
- **Scikit-learn**: Clustering (e.g., DBSCAN, KMeans)
- **Folium / Kepler.gl**: Interactive map visualizations
- **QGIS** *(optional)*: Spatial analysis and map styling

---

## Key Features

### 1. **Earthquake Heatmaps**
- Visualizes frequency and intensity of earthquakes over Japan’s map
- Uses color gradients to indicate seismic density

### 2. **Prefecture-Level Statistics**
- Number of earthquakes per region
- Average magnitude and depth
- Bar charts and summary tables

### 3. **Clustering Analysis**
- Uses DBSCAN or KMeans to detect seismic clusters
- Identifies high-risk seismic zones

### 4. **Risk Zone Mapping**
- Integrates earthquake data with administrative boundaries
- Highlights high-risk prefectures

---

## Sample Results

- Tokyo and Tohoku regions exhibit higher seismic activity
- Depth analysis reveals shallow earthquakes are more frequent in coastal zones
- DBSCAN clusters show strong seismic zones around tectonic boundaries

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/japan-earthquake-geo.git
   cd japan-earthquake-geo
