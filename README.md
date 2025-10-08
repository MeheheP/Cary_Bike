# Cary Bike Analysis

## Project Overview
This project analyzes bicycle safety and infrastructure in Cary, North Carolina, leveraging open data and spatial analysis to identify high-risk areas and recommend ways to make cycling in Cary safer and more accessible. By integrating bike route networks, crash data, parks, eco-counter monitoring, and points of interest, this study provides actionable insights for city planners, cyclists, and the broader public.

---

## Key Datasets

- **Bike Routes:**  
  Source: Town of Cary Open Data Portal  
  Description: 250 route segments with facility type, status (existing/planned), speed limit, and GIS data.

- **Crash Data:**  
  Source: North Carolina Department of Transportation  
  Description: Locations and severities of bicycle-involved crashes with temporal and environmental details.

- **Parks & Recreation:**  
  Source: Town of Cary  
  Description: 867 park locations, used to understand recreational access and safety proximity.

- **Eco-Counter Sites:**  
  Source: Capital Area Metropolitan Planning Organization  
  Description: 40 locations monitoring bicycle/pedestrian traffic volumes.

- **Points of Interest:**  
  Source: Town of Cary  
  Description: 70 schools, centers, and public facilities for destination mapping.

---

##  Major Visualizations

- **Interactive Safety Score Map:**  
  Color-coded bike route segments show safety scores (green = safer, yellow/orange = moderate concern).  
  Additional layers for parks (green markers), eco-counters (purple markers), and community POIs (blue markers).
  Also check out cras_crash_risk map overlayed on bike route .
---

##  Main Findings & Insights

- Biking risk varies significantly across different route types and areas.
- Routes with higher speed limits, fewer facilities, or proximity to intersections tend to have elevated crash risk.
- Certain parks and neighborhood connectors emerge as safer routes.
- Suggested improvements include targeted infrastructure upgrades in moderate and higher-risk segments, especially where crash clusters were identified.
- Increased eco-counter deployment in under-monitored zones can help direct future safety investments.
- Recommendations are data-driven and designed to support ongoing city planning and safety efforts.

---

##  How To Run

- Open the provided Jupyter notebook (`Cary_Bike.ipynb`) in your environment (Jupyter Lab or Notebook).
- Ensure the required Python packages are installed (`pandas`, `plotly`, `matplotlib`, etc.).
- Place the required datasets ( use provided sample data/links) in the specified `data/` directory.
- Run all notebook cells from top to bottom for reproducibility and output generation.

---


---

## 🔗 Data Sources

- [Town of Cary Open Data Portal](https://data.townofcary.org/)
- [NC Department of Transportation](https://www.ncdot.gov/)
- [Capital Area MPO](https://www.campo-nc.us/)

---

## 📢 Contact & Feedback
If you have questions, suggestions, or would like to collaborate, please contact or open an issue in this repository.

---


