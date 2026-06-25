# global-production-analysis
This repository features an end-to-end data analysis pipeline exploring 40 years of global production dynamics (1984 – 2024) and its relationship with geopolitical stability.

# Global Production Trends & Economic Stability Analysis (1984 - 2024)

An end-to-end data analysis project exploring 40 years of global production data. This project investigates production outputs across continents and specific world regions, while also correlating production shifts with country-level political stability metrics sourced from the Worldwide Governance Indicators (WGI).

##  Key Features & Insights
* **Continental Breakdown:** Tracks long-term production shifts (e.g., Asia's ~236% growth vs. Europe's decline since 1984).
* **Regional Deep Dive:** Granular breakdown across 14 distinct world regions (EAS, NAM, CAS, WAS, etc.).
* **Geopolitical Correlation:** Heatmaps and trend lines illustrating how production maps against Stable, Fair, Unstable, and Extremely Unstable manufacturing hubs.

##  Dataset Overview
The analysis utilizes an Excel database (`6.1. Total_World_Production.xlsx`) containing multiple structural sheets:
* `6.1.1.by Continents`
* `6.1.2.by World Regions`
* `6.1.5.by Political Stability`

##  Tech Stack & Libraries
* **Language:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`

##  Sample Visualizations Covered
1. **Production Trend of Countries:** Time-series line plots using melted (long-form) data structures tracking total output by continent.
2. **Growth Rate Aggregations:** Comparative percentage growth analysis from baseline (1984) to present day.
3. **Stability Heatmaps:** Pivot-table generated heatmaps displaying production risks over time.

##  Getting Started

### Prerequisites
Ensure you have Python installed along with the following packages:
```bash
pip install numpy pandas matplotlib seaborn openpyxl
