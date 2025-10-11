# Part III – Final Project Write-up

## Change for the past week
The creation of this final project was guided by a clear understanding of the intended audience, a structured design process, and iterative adjustments to make the story both accessible and impactful. From the beginning, the audience was defined as a general but data-aware public—people interested in understanding the environmental, performance, and safety implications of changing vehicle trends, including the growing dominance of pickup trucks and the slower-than-expected adoption of EVs. To better tailor the narrative, I have interviwed with people with below characterisrics: young environmentally conscious students, mid-career office workers, and car owners who follow the auto market but are not experts. User interviews revealed their needs: clarity on the scale of environmental gaps, straightforward chart labeling, and relatable context. I also got a valuable opinion from them that my visualization would be more impressive if I focous my audience to people who planning to buy a new car.

Based on this, I redesigned my visualizations to emphasize clean, intuitive storytelling, for example, replacing abstract color gradients with a light-to-dark red scale to show the widening CO₂ vs. horsepower gap, and segmenting timelines into distinct eras for clearer trend comparison.

The overall workflow combined structured data storytelling with technical visualization. In earlier phases, I gathered and cleaned vehicle performance and emissions data, then designed and tested several charting strategies. After conducting user testing in Part II, I identified points of confusion—particularly around dual-axis charts and color scales—and addressed them by simplifying legends, adjusting typography, and improving chart annotations. Each visualization was intentionally chosen to lead the audience step by step: beginning with long-term CO₂ emission trends, then moving into horsepower comparisons, safety outcomes, and finally EV adoption as a policy contrast. The design process emphasized accessibility over technical complexity, ensuring that non-experts could follow the narrative without losing the underlying data integrity.

I also found during the interview that the content I have seems bit too much for 1 minutes. Another change is that I choose to get my focus more on just one trend: increase of pickup, without mention anythibg related to the EV ratio, to make my story more easy to understand in one minutes.

I have also add Call-for-action, reference, and AI acknowledgement to my final presentation.

## Sections Included
- [Part I – Project Pitch]：https://taiyuan2490.github.io/data-viz-final
- [Part II – Narrative Development]： https://taiyuan2490.github.io/data-viz-final/part2
- [Part III – Final Reflection]： https://taiyuan2490.github.io/data-viz-final/part3


## Link
Link to shorthand： https://preview.shorthand.com/UNo9o2y1QLRCBxsL

Link to partI: https://taiyuan2490.github.io/data-viz-final/

Link to partII: https://taiyuan2490.github.io/data-viz-final/part2


## Reference
### Picture 
Image: “U.S. Car Market” by Xetai Hanoi, 2024, via xetaihanoi.edu.vn.
Link: https://xetaihanoi.edu.vn/wp-content/uploads/2024/07/thi-truong-xe-hoi-my-66a79f.webp

### Data Sources

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

### AI usage
-- I used GitHub Copilot to assist in identifying relevant and reputable data sources by generating prompt-based search suggestions.
Example prompt: “Find official and open datasets on U.S. vehicle CO₂ emissions, EV adoption by country, and light truck sales.”
This helped me quickly locate high-quality data from the EPA, FRED, Our World in Data, and EEA, which became the backbone of my analysis.

-- Copilot also supported code refinement for visualizations in Python, helping me structure clean Matplotlib plots and apply consistent design choices (e.g., sequential red color gradients, axis formatting, and bar chart grouping).
Example prompt: “Refactor my Matplotlib bar chart code to make it cleaner, use one color gradient from light red to dark red, and improve label readability.”
These suggestions improved the visual clarity and consistency of my charts.

-- I used Copilot to streamline repetitive coding tasks, such as loading CSVs, grouping data, and adjusting legends and annotations to fit the story flow.
Example prompt: “Write Python code to load multiple CSV files, merge by year, and generate grouped bar plots with clear legends and axis labels.”
This accelerated the technical work, allowing me to spend more time on narrative structure and audience-centered design.

  
