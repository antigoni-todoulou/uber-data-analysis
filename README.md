# uber-data-analysis
Data analysis and visualisation of Uber pickup demand using Python and Jupyter Notebook.
 
## Project Overview
 
This project explores Uber pickup demand in New York City using over 13 million ride records. The analysis focuses on pickup patterns across time, dispatch bases, airports and geographic locations.
 
## Objectives
 
- Clean and preprocess Uber trip data
- Identify temporal pickup trends
- Analyse hourly and weekday demand patterns
- Evaluate dispatch base activity using Pareto analysis
- Compare demand across NYC airports
- Visualise pickup density through interactive maps
 
## Dataset
 
The project uses Uber pickup datasets covering multiple months of NYC ride activity, including:
 
- Pickup timestamps
- Geographic coordinates
- Dispatching base numbers
- Airport location identifiers
 
## Data Preparation
 
The following data-cleaning steps were performed:
 
- Duplicate detection and removal
- Missing value inspection
- Datetime conversion
- Feature engineering:
  - Month
  - Weekday
  - Day of month
  - Hour
  - Minute
   
## Analysis Performed
 
### 1. Monthly Pickup Trends
 
- Identified months with the highest Uber demand
- Compared pickup volume across January–June
 
### 2. Weekday Demand Analysis
 
- Built cross-tabulations of pickups by month and weekday
- Visualised monthly demand across different days of the week
 
### 3. Hourly Demand Analysis
 
- Analysed ride volume by hour of day
- Compared hourly demand patterns across weekdays
- Created interactive Plotly line charts
 
### 4. Dispatch Base Analysis
 
- Ranked dispatch bases by ride volume
- Calculated cumulative ride percentages
- Built a Pareto chart to identify the most important dispatch bases
 
### 5. Airport Demand Analysis
 
Compared pickup activity for:
 
- JFK Airport
- LaGuardia Airport (LGA)
- Newark Airport (EWR)
 
and analysed hourly airport demand patterns.
 
### 6. Data Engineering
 
- Combined multiple monthly CSV datasets into a unified DataFrame
- Exported cleaned data to:
- CSV
- JSON
- SQLite database
 
### 7. Geospatial Analysis
 
- Created interactive Folium maps
- Built animated hourly heatmaps showing pickup density across New York City
- Visualised how pickup hotspots evolve throughout the day
 
## Technologies Used
 
- Python
- Pandas
- NumPy
- Plotly
- Matplotlib
- Seaborn
- Folium
- SQLite
- SQLAlchemy
- Jupyter Notebook
 
## Key Skills Demonstrated
 
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Time Series Analysis
- Geospatial Visualisation
- Interactive Dashboard Visualisation
- Data Export & Storage
- SQL Database Integration

## Data Access
 
The original dataset can be downloaded from:
 
https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city
 
Note: Raw data files are not stored in this repository because of their size.

## Files
 
- `Uber_Data_Analysis.ipynb` — Main analysis notebook
 
## Author
 
Antigoni Todoulou
