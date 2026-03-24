# Visualising-Geospatial-Data
This project presents an exploratory geospatial and statistical analysis of Airbnb listings across New York City's five boroughs. Using Python-based visualisation tools, listing distribution, nightly pricing patterns, room-type composition, and availability are examined spatially and analytically

Project Structure

├── AB_NYC_2019.csv               # Source dataset (Kaggle)
├── jupyter_map_snippet.py        # Jupyter-ready code for map & charts
├── nyc_airbnb_map.html           # Interactive Folium map output
├── chart1_price_borough.png      # Avg nightly price by borough
├── chart2_room_type.png          # Room type distribution (donut)
├── chart3_price_band.png         # Listing count by price band
├── chart4_availability.png       # Availability vs. listing count
└── Task4_Geospatial_Report.docx  # Full written report

## Overview

This project presents an exploratory geospatial and statistical analysis of Airbnb listings across New York City's five boroughs. Using Python-based visualisation tools, listing distribution, nightly pricing patterns, room-type composition, and availability are examined spatially and analytically.

---

## Project Structure

```
├── AB_NYC_2019.csv               # Source dataset (Kaggle)
├── jupyter_map_snippet.py        # Jupyter-ready code for map & charts
├── nyc_airbnb_map.html           # Interactive Folium map output
├── chart1_price_borough.png      # Avg nightly price by borough
├── chart2_room_type.png          # Room type distribution (donut)
├── chart3_price_band.png         # Listing count by price band
├── chart4_availability.png       # Availability vs. listing count
```

---

## How to Run

**1. Install dependencies**
```bash
pip install pandas folium matplotlib numpy
```

**2. Place the dataset in your working directory**
```
AB_NYC_2019.csv
```

**3. Run the snippet in Jupyter Notebook**
```bash
jupyter notebook
```
Open `jupyter_map_snippet.py`, execute each cell in order. All charts and the interactive map will be generated and saved automatically.

---

> Dgomonov (2019). *New York City Airbnb Open Data* [Dataset]. Kaggle.
> [https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
