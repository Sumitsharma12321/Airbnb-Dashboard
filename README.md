# Airbnb Performance Dashboard

## Overview

This dashboard provides a comprehensive view of Airbnb's platform performance, covering listing growth trends, city-level market share, pricing breakdowns, and guest ratings across 10 major global cities. It is structured into two main pages: **New Listings (Growth Timeline)** and **Market Share & Ratings by City**.

-----
<img width="796" height="548" alt="image" src="https://github.com/user-attachments/assets/dbe6166c-a47e-4449-9442-16d3186f1f34" />
<img width="605" height="458" alt="image" src="https://github.com/user-attachments/assets/27088662-659d-4fb4-816e-663e64b362d0" />


## Key Metrics (Summary Cards)

| Metric | Value |
|---|---|
| Total Listings | 279,712 |
| Cities Covered | 10 |
| Total Hosts | 182,024 |
| Property Types | 144 |
| Total Reviews | 5,373K |

---

## Page 1 — New Listings Timeline

### What It Shows
A line chart tracking the total number of new listings over time (2008–2021), broken down by property type:
- **Entire Place**
- **Private Room**
- **Hotel Room**
- **Shared Room**

### Business Lifecycle Phases
The chart is segmented into six business phases:

| Phase | Period | Key Highlights |
|---|---|---|
| Introduction | 2008–2011 | Slow early growth; minimal listings |
| Growth | 2011–2014 | Rapid expansion across all listing types |
| Maturity | 2014–2016 | Peak listings reached; Entire Place dominates |
| Decline | 2016–2017 | Restraint due to tightening local regulations |
| Reinvention | 2018–2019 | New growth phase; profitability established |
| COVID-19 | 2020–2021 | Sharp decline across all listing types |

### Key Insights
- **2015** was the peak year for new listings across all property types.
- **2016–2017** saw a slowdown driven largely by stricter local regulations, yet Airbnb became profitable in the second half of 2016. **2017** was its first full profitable year.
- A **new growth phase** started from 2018 but was interrupted by the **COVID-19 pandemic** in 2019–2020.
- **Entire Place** listings consistently lead in volume, followed by **Private Rooms**.

---

## Page 2 — Market Share by City & Ratings

### Market Share by City

A Pareto-style bar chart showing listing distribution across 10 cities, split by Superhost vs. non-Superhost listings, with a cumulative percentage line.

**Cities covered (by listing volume, high to low):**
Paris · New York · Sydney · Rome · Rio de Janeiro · Istanbul · Mexico City · Bangkok · Cape Town · Hong Kong

**Key Insights:**
- **Paris, New York, and Sydney** together account for nearly half of all listings and **48% of total reviews**.
- **Paris** leads with the highest listings and reviews — likely driven by hotel room prices being roughly **twice as expensive** as comparable Airbnb options.
- Superhost listing share varies widely by city (from ~23% in Paris to ~100% in New York by cumulative share).

---

### Average Pricing by Property Type

| Property Type | Avg. Price |
|---|---|
| Hotel Room | $800 |
| Entire Place | $673 |
| Shared Room | $580 |
| Private Room | $462 |

---

### City Ratings

#### Overall Average Rating (out of 100)

| Rank | City | Avg Rating |
|---|---|---|
| 1 | Mexico City | 94.8 |
| 2 | Rio de Janeiro | 94.6 |
| 3 | Cape Town | 94.4 |
| 4 | New York | 93.8 |
| 5 | Rome | 93.5 |
| 6 | Sydney | 93.2 |
| 7 | Paris | 93.1 |
| 8 | Bangkok | 93.0 |
| 9 | Istanbul | 91.1 |
| 10 | Hong Kong | 89.7 |

#### Detailed Ratings (out of 10) — Selected Cities

| City | Accuracy | Cleanliness | Communication | Location | Value |
|---|---|---|---|---|---|
| Mexico City | 9.70 | 9.56 | 9.76 | 9.80 | 9.55 |
| Rio de Janeiro | 9.64 | 9.39 | 9.76 | 9.76 | 9.30 |
| Cape Town | 9.61 | 9.53 | 9.73 | 9.72 | 9.48 |
| New York | 9.59 | 9.27 | 9.71 | 9.60 | 9.37 |
| Paris | 9.60 | 9.21 | 9.71 | 9.69 | 9.28 |
| Bangkok | 9.49 | 9.41 | 9.60 | 9.24 | 9.34 |
| Istanbul | 9.26 | 9.05 | 9.53 | 9.43 | 9.17 |
| Hong Kong | 9.21 | 8.99 | 9.43 | 9.55 | 8.99 |

**Key Insights:**
- **Mexico City** and **Rio de Janeiro** are the best-rated cities overall.
- **Hong Kong** and **Istanbul** score the lowest overall.
- **Cleanliness** and **Value for Money** are the two dimensions that consistently score the lowest across all cities.

---

## Data Scope & Limitations

- Data covers **10 major global cities** and may not be representative of all Airbnb markets.
- Timeline data runs from **2008 to approximately 2021**, capturing Airbnb's full business lifecycle including the COVID-19 impact.
- Pricing figures represent **averages** and may vary significantly by neighbourhood, season, and availability.
- Ratings are aggregated across all listings per city and may mask intra-city variation.
