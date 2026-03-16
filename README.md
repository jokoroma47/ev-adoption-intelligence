# The Electric Revolution — EV Adoption & Market Intelligence

A data analytics project mapping the growth and composition 
of electric vehicle adoption across Washington State using 
194,223 vehicle registrations spanning nearly three decades.

---

## Overview

Washington State is one of America's leading EV markets. 
I built this project to understand who is driving adoption, 
where it is concentrated geographically, how the market 
has evolved year on year, and which manufacturers and models 
are winning the electric revolution.

The dataset covers all EV registrations on record with the 
Washington State Department of Licensing — 194,223 vehicles 
across 42 manufacturers, 756 cities and model years from 
1997 to 2025.

---

## What I Found

- Tesla holds 43.9% market share — nearly 6x the nearest 
  rival Chevrolet (7.5%). The Model Y alone represents 1 
  in every 5 EVs registered in Washington State
- 2023 produced 59,664 new registrations — more than the 
  entire period from 1997 to 2020 combined, a 5.8x 
  acceleration in under a decade
- Non-Tesla manufacturers first exceeded Tesla in 2022 
  (14,387 vs 13,767), signalling a market maturing beyond 
  a single dominant player
- King County holds 51.5% of all registrations — Seattle's 
  tech workforce and charging infrastructure drive 
  disproportionate adoption
- 78.4% of EVs are pure battery electric (BEV), with PHEV 
  share declining as consumers increasingly choose full electric
- Manufacturer strategies diverge sharply: Jeep = 100% PHEV, 
  Toyota = 90% PHEV, while Tesla, Nissan and Volkswagen 
  are 100% BEV
- Average BEV range (reported vehicles) is 196.7 miles — 
  6.4x the average PHEV range of 30.9 miles
- The Tesla Model S holds the maximum recorded range at 
  337 miles — followed by Model 3 at 322 miles

---

## Data Methodology

The raw dataset required 12 cleaning steps before analysis. 
Key decisions include treating Electric_Range = 0 as 
unreported (not zero-range) — confirmed by 100% correlation 
with unknown CAFV eligibility status. Base_MSRP = 0 on 98.3% 
of records was similarly treated as unreported rather than 
zero price, a known WA DOL data collection gap.

---

## Dashboard

Five interactive pages covering — an executive overview 
with headline KPIs, market intelligence including 
manufacturer and model rankings, geographic distribution 
by county and city, vehicle technology analysis including 
range distribution, and growth trend analysis from 2011 
to 2024.

[View the live dashboard here](https://jokoroma47.github.io/ev-adoption-intelligence)

---

## Tools Used

Power BI · MySQL · Python · HTML · CSS · JavaScript

---

## Files

| File | Description |
|------|-------------|
| index.html | Interactive web dashboard |
| data/EV_Population_Cleaned.csv | Cleaned dataset |


---

## Contact

