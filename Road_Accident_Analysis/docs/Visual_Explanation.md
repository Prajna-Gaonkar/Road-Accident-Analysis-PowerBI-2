# Visual Explanation — Road Accident Analysis

Use this file to document the final fields and measures used in each visual. Confirm the exact measure names in Power BI before filling in any placeholders.

| Visual | Purpose | Fields / measures to verify |
|---|---|---|
| KPI cards | Show headline accident/casualty metrics | Confirm the title and exact measure for each card. Several cards appeared with the same “CY Accidents” title in the provided screenshot. |
| Vehicle Type table | Compare casualties by vehicle group | Vehicle Type (groups), CY Casualties |
| Monthly trend | Compare current-year and previous-year casualties by month | Month, Year, CY Casualties, PY Casualties |
| Urban/Rural donut | Compare casualties by area type | Urban/Rural area, casualty measure |
| Weather bar chart | Compare casualties by weather category | Weather Conditions, casualty measure |
| Road Type bar chart | Compare current-year casualties by road type | Road Type, CY Casualties |
| Light Conditions donut | Compare casualties in daylight and darkness | Light Conditions, casualty measure |
| Location map | Explore geographic distribution | Geographic/local authority field and accident/casualty measure used for map size or tooltip |
| Slicers | Filter the report | Road Surface Conditions, Weather Conditions |

## Final QA checklist
- [ ] Each KPI card has a unique, accurate title.
- [ ] All measures display the intended units and number format.
- [ ] The monthly chart uses the intended current and previous years.
- [ ] Blank/unknown categories are handled intentionally.
- [ ] Slicers filter all intended visuals.
- [ ] Totals reconcile with the source data and filter context.
- [ ] The map uses the correct geographic field and does not imply precision beyond the source data.
- [ ] DAX formulas and exact source dataset details are added after verification.
