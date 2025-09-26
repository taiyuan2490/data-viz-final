# Final Project · U.S. Auto Market Visualization (2000–2024)

## Executive Summary
This project explores how U.S. consumer preferences in the automobile market have shifted over the past two decades, and what this means for emissions, safety, and global positioning.  
The story is structured around four pillars:
1. **Preferences** — From sedans to SUVs and pickups.  
2. **Environment** — How efficiency and electrification shaped emissions.  
3. **Safety** — Trends in traffic fatalities and pedestrian risk.  
4. **Market portrait** — Registrations, vehicle miles traveled, and sales volume.

The analysis uses publicly available datasets 

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
## Data Sources

- **[EPA Automotive Trends Report](https://www.epa.gov/automotive-trends/explore-automotive-trends-data)**  
  Annual data on CO₂ emissions, horsepower, vehicle weight, and fuel economy for U.S. cars and trucks.

- **[FRED / BEA Vehicle Sales](https://fred.stlouisfed.org/series/LTRUCKSA)** (Light trucks) and [All Light Vehicles](https://fred.stlouisfed.org/series/ALTSALES)  
  Monthly sales (seasonally adjusted annual rates) for cars vs. light trucks in the U.S.

- **[Our World in Data — Electric Car Sales Share (IEA)](https://ourworldindata.org/grapher/electric-car-sales-share)**  
  Share of new car sales that are electric, 2015–2024, across U.S., EU, China, and Japan.

- **[European Environment Agency (EEA) — New Car CO₂ Emissions](https://www.eea.europa.eu/data-and-maps/data/co2-cars-emission-18)**  
  Sales-weighted average CO₂ emissions of new cars sold in the EU (2000–2023).

- **[Bureau of Transportation Statistics (BTS) / NHTSA Fatality Rate Data](https://www.bts.gov/content/traffic-fatalities-and-rates)**  
  Fatalities per 100 million vehicle miles traveled, U.S. (historical series).

- **[FHWA Highway Statistics — Vehicle Miles Traveled & Registrations](https://www.fhwa.dot.gov/policyinformation/statistics.cfm)**  
  Total U.S. vehicle registrations and annual vehicle miles traveled (VMT).


---

## Sketches (Initial Ideas)

1. **Market Share Line Chart**  
 Title: “By 2024, light trucks dominate U.S. auto sales.”  
 X-axis: year, Y-axis: % of sales (cars vs trucks).  

2. **CO₂ vs Horsepower Dual Axis**  
 Title: “Bigger and stronger cars slowed U.S. emissions progress.”  

3. **EV Adoption by Region**  
 Title: “U.S. lags Europe and China in EV adoption.”  

4. **Fatalities per 100M VMT**  
 Title: “U.S. road safety improved overall, but pedestrian risks remain.”  

5. **Market Snapshot Cards**  
 Registrations, VMT, annual sales pace.

---

## Data Dictionary
- `share_ltrucks`: Share of light trucks in total U.S. light vehicle sales.  
- `ev_share`: EV share of new car sales (2015–2024).  
- `co2_gpm`: Sales-weighted CO₂ emissions, grams per mile (EPA).  
- `hp`: Sales-weighted horsepower (EPA).  
- `fatalities_rate`: Fatalities per 100M vehicle miles traveled.  
- `registrations`: Total number of registered vehicles in the U.S.  
- `vmt`: Vehicle miles traveled annually.  

---

## Conclusion
- **Preference Shift**: U.S. consumers reshaped the market toward larger vehicles.  
- **Environmental Externality**: CO₂ reductions slowed; electrification is now the main corrective force.  
- **Safety Context**: Roads are safer overall, but pedestrians face higher risks from tall SUVs/pickups.  
- **Market Portrait**: The U.S. auto market is defined by scale, light-truck dominance, and a lag in EV transition compared to global peers.

---

### Navigation
- [Charts (interactive)](charts.html) *(to be added later)*  
- [GitHub Repository](../)  


