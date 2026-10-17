# Road Accident Analysis Dashboard | Power BI

## Project Overview
This project uses Microsoft Power BI to explore road accident and casualty patterns. The interactive dashboard brings key indicators, monthly trends, road characteristics, environmental conditions, and geographic distribution together in one report.

## Objectives
- Monitor key accident and casualty indicators.
- Compare monthly casualty trends across years.
- Explore casualties by vehicle type, road type, urban/rural area, and light conditions.
- Examine how weather and road-surface conditions relate to casualty counts.
- Explore the geographic distribution of recorded accidents using a map.

## Tools
- Microsoft Power BI Desktop
- Power Query for data preparation
- DAX for measures and year-over-year analysis

## Dashboard Features
1. **KPI cards** — headline casualty and accident measures. Confirm each card's title and measure in Power BI before publishing; the screenshot used during documentation showed repeated “CY Accidents” titles on several cards.
2. **Vehicle type summary** — casualty counts grouped by vehicle category.
3. **Monthly casualty trend** — compares current-year and previous-year casualties by month.
4. **Urban/Rural comparison** — donut chart showing the casualty split by area type.
5. **Weather conditions** — casualty counts for Fine, Rainy, Snow, Other, and blank/unknown categories.
6. **Road type** — current-year casualties by road type.
7. **Light conditions** — casualty split by daylight and dark conditions.
8. **Geographic map** — displays accident locations by local authority/geographic area.
9. **Slicers** — road-surface and weather-condition filters for interactive exploration.

## Key Insights to Investigate
Use the dashboard filters and tooltips to validate insights such as:
- Which vehicle categories account for the largest number of casualties?
- How do monthly casualty counts compare between the selected year and the previous year?
- How do casualty counts differ between urban and rural areas?
- Which road types have the highest casualty counts?
- How do casualty counts vary across light, weather, and road-surface conditions?
- Which geographic areas show higher concentrations of recorded accidents?

> Write final insight statements only after checking the data and filters in Power BI. Avoid treating association as proof that a condition caused an accident.

## Data Preparation
Data cleaning was performed in Power Query. Review the query steps before publishing and document any removed blank rows, null handling, or category replacements. Missing values should be handled column by column rather than removing every row that contains a null.

## DAX Measures
The report includes current-year and previous-year measures and year-over-year comparisons. For exact formulas, open the PBIX and copy the final measures into [`docs/Visual_Explanation.md`](docs/Visual_Explanation.md) or add them below once verified.

## Repository Structure
```text
Road-Accident-Analysis-PowerBI/
├── README.md
├── .gitignore
├── powerbi/
│   └── Road_Accident_Analysis.pbix
└── docs/
    └── Visual_Explanation.md
```

## How to Use
1. Download `powerbi/Road_Accident_Analysis.pbix`.
2. Open it using Power BI Desktop.
3. Refresh the data source if needed and follow any prompts to update the source path.
4. Use the slicers and visual interactions to explore the report.

## Limitations
- Findings depend on the coverage, definitions, and quality of the source dataset.
- Blank or unknown categories can affect chart totals and should be reviewed.
- Counts show patterns in the available data; they do not by themselves establish causation.

## Resume Project Description
**Road Accident Analysis Dashboard | Power BI**  
Developed an interactive Power BI dashboard to analyze accident and casualty patterns across time, vehicle categories, road types, weather, lighting, urban/rural areas, and geographic locations. Used Power Query for data preparation and DAX measures for KPI reporting and year-over-year trend comparison.

## Interview Introduction
“I built a Power BI dashboard to explore road accident and casualty data from multiple perspectives. It includes KPI cards, a year-over-year monthly trend, vehicle and road-type breakdowns, urban/rural and light-condition comparisons, weather and road-surface filters, and a geographic map. I used Power Query to prepare the data and DAX measures to calculate key indicators and compare yearly trends. The goal is to make patterns easier to explore interactively and support data-driven investigation.”
