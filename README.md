# US Traffic Accidents Analysis

## Project Description  
This project analyzes **traffic accident data** across the United States to identify patterns related to **road conditions, weather**, and **time of day**.  
It also visualizes **accident hotspots** and contributing factors using both static and interactive visualizations.

---

## Dataset  
- **Source:** [US Accidents (2016–2023) — Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
- **Records:** Over 7 million accident reports  
- **Attributes Used:** Time, location, weather, visibility, humidity, wind speed, severity  

---

## Objectives  
- Examine accident distribution across **different times of day and months**  
- Analyze **weather and visibility conditions** contributing to accidents  
- Create **interactive visualizations** for exploratory insights  
- Generate a **heatmap** of U.S. accident hotspots  

---

## Tools & Libraries  
- **Python**  
- **pandas, numpy** — Data analysis  
- **matplotlib, seaborn, plotly** — Visualization  
- **folium** — Geospatial hotspot mapping  
- **kagglehub** — Direct Kaggle dataset access  

---

## Key Insights  
- Most accidents occur during **rush hours (7–9 AM, 4–6 PM)**  
- **Clear and partly cloudy** weather account for the majority of cases  
- **Low visibility** often correlates with **higher severity levels**  
- Major hotspots observed in **California, Texas, and Florida**  

---

## Visualizations  
- **Bar Charts & Boxplots:** Time, severity, and weather patterns  
- **Interactive Plotly Graphs:** Monthly and hourly trends  
- **Folium Heatmap:** Visual representation of accident concentration  

---

## Files in Repository  
| File | Description |
|------|--------------|
| `us_accidents_analysis.ipynb` | Google Colab notebook with full code |
| `us_accidents_hotspots.html` | Interactive heatmap of U.S. accidents |
| `README.md` | Project documentation |

---

## How to Run  
1. Open `us_accidents_analysis.ipynb` in **Google Colab**  
2. Run the setup cell to install dependencies and download the dataset  
3. Execute all cells sequentially to view analysis and visualizations  

