# Air Quality Analysis and Visualization

## Overview
This project analyzes and visualizes Air Quality Index (AQI) data to understand pollution trends, identify the most polluted regions, and break down AQI contributions by pollutants. The project includes geospatial heatmaps, comparison charts, and pollutant breakdowns.

---

## Features
- Geospatial heatmap of AQI levels across countries.
- Comparison of AQI by country and pollutant contribution breakdown.
- Identification of top 10 most polluted cities.
- Visualization of AQI category distribution.

---

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: 
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for data visualization
  - `folium` for geospatial heatmaps

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shehab125/Air-Quality-Analysis-and-Visualization.git
   cd Air-Quality-Analysis-and-Visualization
   ```

---

## Dataset
- **Source**: `AQI and Lat Long of Countries.csv`
- **Description**: Contains AQI values, geographic coordinates, and pollutant-specific AQI values for various countries and cities.

---

## How to Use
1. **Run the Script**:
   ```bash
   DS project.ipynb
   ```
2. **Visualizations**:
   - Geospatial heatmap of AQI.
   - Top 20 countries with the highest average AQI.
   - Pollutant contribution breakdown.
   - AQI category distribution pie chart.
   - Top 10 most polluted cities.

---

## Project Structure
```
Air-Quality-Analysis/
├── AQI and Lat Long of Countries.csv  # Dataset
├── aqi_analysis.py                   # Main Python script
├── README.md                         # Project documentation
```

---

## Results
### Geospatial Heatmap
A heatmap visualizing AQI levels geographically using latitude and longitude.

### AQI Comparison by Country
Bar chart of the top 20 countries with the highest average AQI.

### Pollutant Breakdown
Bar chart showing average AQI contribution by pollutants (CO, Ozone, NO2, PM2.5).

### AQI Category Distribution
Pie chart displaying AQI categories (e.g., Good, Moderate, Unhealthy).

### Top 10 Most Polluted Cities
Bar chart highlighting cities with the highest AQI values.
---

## Acknowledgments
- `folium` for geospatial visualizations.
- Datasets for AQI analysis.

---

## Contact
For questions or suggestions, please contact shehab hosny at shehabhosny889@gmail.com
