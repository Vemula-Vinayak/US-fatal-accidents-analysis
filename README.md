# U.S. Fatal Traffic Accidents Analysis (2022)

## Overview
This project performs exploratory data analysis (EDA) on 2022 fatal motor vehicle crash data from the Fatality Analysis Reporting System (FARS). The goal is to uncover spatial, temporal, and environmental patterns contributing to crash severity and frequency across the United States.

---

## Dataset
- Source: FARS 2022
- ~39,000 fatal crash records
- Features include:
  - Time & Hour
  - State & Geographic Coordinates
  - Weather Conditions
  - Lighting Conditions
  - Number of Vehicles
  - Fatalities per Crash

---

## Objectives
- Analyze temporal patterns (hourly, weekday vs weekend)
- Examine geographic distribution of fatal crashes
- Evaluate impact of weather and lighting conditions
- Adjust crash rates per 100K population
- Identify high-risk regions and peak crash times

---

## Key Visualizations

- Interactive Bubble Map (GPS-based crash visualization)
- Choropleth Maps (Crash counts by state)
- Population-adjusted risk maps
- Hourly crash histograms
- Weekday vs Weekend comparisons
- Weather severity box plots
- Heatmap of crash concentration
- Time-series crash trends

---

## Key Insights

- Evening hours (5–8 PM) show highest fatal crash frequency.
- Poor lighting and adverse weather increase fatality severity.
- States like Texas and California have highest raw crash counts.
- Population-adjusted metrics provide more accurate risk comparisons.
- Weather significantly interacts with crash severity patterns.

---

## Technologies Used

- Python
- Pandas
- Plotly
- Seaborn
- Mapbox
- Jupyter Notebook

---

## How to Run

1. Install required libraries:
   ```
   pip install pandas plotly seaborn
   ```
2. Open:
   ```
   EDA_Project2_Final_code.ipynb
   ```
3. Run all cells to generate interactive maps and charts.

---

## Impact

This project demonstrates advanced EDA, interactive visualization, and insight-driven storytelling using real-world government data.
