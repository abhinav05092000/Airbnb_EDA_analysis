# Airbnb_EDA_analysis
# Exploratory Data Analysis — Airbnb NYC Listings

**Author:** Abhinav Singh Baghel
**Track:** Data Analytics Internship — Task 2 (Day 2)

## Overview
This project performs exploratory data analysis (EDA) on the New York City Airbnb Open Data (2019) dataset, containing 48,895 listings across 16 attributes. The goal was to identify patterns, relationships, outliers, and trends in the data before drawing any conclusions.

## Approach
1. **Data understanding** — loaded the dataset, reviewed structure with `.info()` and `.describe()`, and checked for missing values.
2. **Correlation analysis** — built a correlation heatmap across numeric features to see which variables relate to `price`.
3. **Visual analysis** — created 6 visualizations, each paired with a written observation:
   - Price distribution (histogram)
   - Price by room type (boxplot, outlier detection)
   - Listings by borough (bar chart)
   - Geographic spread of listings colored by price (scatter)
   - Availability vs. number of reviews (scatter)
   - Review activity trend over time (line chart)
4. **Insight synthesis** — summarized the three most important findings from the analysis.

## Tools
- Python
- Pandas
- Matplotlib
- Seaborn

## Files
- `Airbnb_EDA.ipynb` — full notebook with code, outputs, and written observations
- `AB_NYC_2019.csv` — dataset used (source: NYC Airbnb Open Data, 2019)

## Key Findings
1. Location is the dominant price driver, but it doesn't show up in numeric correlation — it only becomes visible through the geographic visualization.
2. Listing supply is heavily concentrated in Manhattan and Brooklyn (~85% combined); other boroughs are minimally represented.
3. Missing review data isn't a data quality issue — it reflects listings with zero reviews, and can be safely imputed as 0 rather than dropped.

## Outcome
The notebook meets the task deliverables: summary statistics, 5+ visualizations with observations, and a "Top 3 insights" section, along with worked answers to the accompanying interview questions.
```
