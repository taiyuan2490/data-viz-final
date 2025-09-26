# Final Project · U.S. Auto Market Visualization (2000–2024)

## Executive Summary
This project explores how U.S. consumer preferences in the automobile market have shifted over the past two decades, and what this means for emissions, safety, and global positioning.  
The story is structured around four pillars:
1. **Preferences** — From sedans to SUVs and pickups.  
2. **Environment** — How efficiency and electrification shaped emissions.  
3. **Safety** — Trends in traffic fatalities and pedestrian risk.  
4. **Market portrait** — Registrations, vehicle miles traveled, and sales volume.

The analysis uses publicly available datasets (EPA, FRED/BEA, OWID, EEA, BTS/NHTSA, FHWA). All visualizations are reproducible with Python and Vega-Lite.

---

## Outline · Story Structure
- **Shift in Consumer Preferences**  
  U.S. light truck share (SUVs + pickups + vans) grew from ~50% in 2000 to nearly 80% in 2024.  
  This change increased average vehicle size and horsepower.  

- **Environmental Impact**  
  Sales-weighted CO₂ emissions fell, but slower than in the EU due to heavier vehicles and slower EV adoption.  
  EV penetration in the U.S. lags behind Europe and China.  

- **Safety Impact**  
  Fatalities per 100M vehicle miles traveled declined, but risks for pedestrians increased due to taller vehicle fronts.  

- **Market Portrait**  
  - Registrations: total U.S. vehicle fleet expanded steadily.  
  - Vehicle miles traveled: rebounded after COVID-19 dip.  
  - Sales: stable around 15–17M units/year, with strong light-truck dominance.  

---

## Data Sources
- **EPA Automotive Trends Report** — CO₂ emissions, horsepower, vehicle weight.  
- **FRED / BEA** — Car vs light truck sales (seasonally adjusted annual rates).  
- **Our World in Data (IEA)** — EV share of new sales, 2015–2024.  
- **European Environment Agency (EEA)** — Sales-weighted CO₂ of new cars in the EU.  
- **Bureau of Transportation Statistics / NHTSA** — Fatalities per 100M vehicle miles.  
- **FHWA** — Vehicle registrations and total miles traveled.

_All sources are open/public domain or CC BY licensed. Data is reproducible and linked in the repository’s `/data/` folder._

---

## Methods & Media
- **Cleaning**: Python (pandas/numpy).  
- **Visualization**: Vega-Lite JSON specs embedded into GitHub Pages.  
- **Structure**:

