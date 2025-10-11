# Final Project · U.S. Auto Market Visualization  
## Executive Summary
This project explores how U.S. consumer preferences in the automobile market have shifted over the past two decades, and what this means for emissions, safety, and global positioning.  
The story is structured around four pillars:
1. **Preferences** — From sedans to SUVs and pickups.  
2. **Environment** — How efficiency and electrification shaped emissions.  
3. **Safety** — Trends in traffic fatalities and pedestrian risk.  

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
---

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
<img width="742" height="247" alt="image" src="https://github.com/user-attachments/assets/408808c2-600e-44b7-bb6e-ce73b94e8b7c" />

**Market Share Line Chart**  

 Title: “By 2024, light trucks dominate U.S. auto sales.”  
 X-axis: year, Y-axis: % of sales (cars vs trucks).
<img width="778" height="502" alt="image" src="https://github.com/user-attachments/assets/577dfbd7-646a-4509-9898-ebf86e53cc10" />

The graph reveals a dramatic shift in U.S. consumer behavior: light trucks surged from niche to mainstream, reflecting changing lifestyles, fuel economics, and design trends—culminating in over 80% market share by 2022.

**CO₂ vs Horsepower**

<img width="442" height="442" alt="image" src="https://github.com/user-attachments/assets/db4fab1f-ef6a-4a35-aa60-37b19aea7be1" />

<img width="768" height="482" alt="image" src="https://github.com/user-attachments/assets/ed12832f-8983-4204-8384-67205567afd5" />


Technology enabled vehicles to gain horsepower while lowering CO₂, but progress was uneven. Cars steadily improved efficiency, reducing emissions even as power rose. 

<img width="796" height="466" alt="image" src="https://github.com/user-attachments/assets/c5acd4af-d28a-4cb1-9f9f-fc9f0cf42f5d" />

Pickups, however, grew heavier and more powerful, with slower CO₂ decline. This divergence explains why U.S. fleetwide emissions progress lagged despite cleaner engines and better fuel economy.  

<img width="832" height="395" alt="image" src="https://github.com/user-attachments/assets/a754e499-6d4f-4dc5-9aed-dbbccea34ea4" />

Technology bring more horsepower, cleaner. howeber, having more horsepower with a pickup generally comes with a price. 

<img width="723" height="429" alt="image" src="https://github.com/user-attachments/assets/17f5deb5-124c-4437-807e-250ca8506f32" />


 **EV Adoption by Region**  
 Title: “U.S. lags Europe and China in EV adoption.”

<img width="793" height="462" alt="image" src="https://github.com/user-attachments/assets/50e8ec16-340e-455b-9e84-d6be47567c8f" />

Half of new car in China are electronic, U.S. on the other hand, only have 10%. The U.S. trails behind Europe and China in EV adoption, with under 10% market share by 2024. Despite global momentum, domestic uptake remains slow—highlighting policy gaps and consumer hesitancy.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6acbfd29-88b5-4a1f-81ca-2e891b080d9a" />

 **Fatalities per 100M VMT**  
 Title: “U.S. road safety improved overall, but pedestrian risks remain.”
<img width="790" height="459" alt="image" src="https://github.com/user-attachments/assets/7ff8dda2-9133-4d63-ab90-35f801d969d1" />


<img width="796" height="389" alt="image" src="https://github.com/user-attachments/assets/9b6507f5-a608-4a23-994d-4e289876be2e" />

As light truck sales surged post-2010, U.S. road fatalities per 100M miles reversed their long decline—raising questions about vehicle design, pedestrian safety, and the unintended consequences of consumer preference shifts.
 
---

---

## Conclusion


Consumer Shift: Since 2000, U.S. buyers have steadily favored pickups and SUVs, with horsepower climbing far faster than in other vehicle classes.

Environmental Tradeoff: While technology made engines cleaner, pickups’ relative CO₂ gap versus cars widened, slowing national emissions progress.

Safety Paradox: Fatalities per mile declined overall, especially in 2000–2010, but the surge in light-truck sales coincided with stalled progress and rising pedestrian vulnerability.

## Method and medium

The final project will combine static charts and interactive visualizations to communicate the evolution of the U.S. auto market. Beyond line charts, I will incorporate diverse visualization types (e.g., heatmaps, bubble charts, geographic maps, and ridgeline plots) to better capture patterns and contrasts.

I plan to use Python (pandas, matplotlib, seaborn, Plotly) for analysis and visualization, with GitHub Pages as the main platform for publishing. Where relevant, I will also integrate geospatial visualizations to highlight national and regional perspectives.

Future extensions may include building an interactive dashboard with Plotly Dash or Streamlit, or experimenting with immersive/interactive media for more engaging storytelling. If needed, I may also use Tableau to supplement complex visualizations and ensure accessibility for broader audiences.


## AI knowledgement
I used generative AI tools (Copilot) to brainstorm visualization ideas, refine narrative framing, and refine Python code templates for data analysis. I reviewed, edited, and validated all outputs. Final analysis and interpretation are my own, with AI treated as a supporting tool, consistent with CMU academic integrity policies.

## Sections Included
- [Part I – Project Pitch]：https://taiyuan2490.github.io/data-viz-final
- [Part II – Narrative Development]： https://taiyuan2490.github.io/data-viz-final/part2
- [Part III – Final Reflection]： https://taiyuan2490.github.io/data-viz-final/part3
