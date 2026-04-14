🌍 Global Health Crisis: Hygiene in Healthcare Facilities
A data analytics report exploring the state of hygiene in healthcare facilities across the world, built using UNICEF data, Python, and Quarto.
---
📋 Project Overview
Millions of people seek medical care every day, yet in many countries the facilities meant to heal them lack basic hygiene services. This project uses UNICEF global data to examine the scale of this crisis and its relationship to economic inequality.
Key Questions Explored
Which countries have the worst hygiene in health facilities?
Is there a relationship between GDP per capita and hygiene quality?
How has the situation changed over time?
---
📁 Project Structure
```
├── report.ipynb              # Main Quarto notebook
├── report.html               # Rendered HTML report
├── style.css                 # Custom CSS styling
├── unicef_indicator_1.csv    # UNICEF hygiene indicator data
├── unicef_indicator_2.csv    # UNICEF supplementary indicator data
└── unicef_metadata.csv       # Country metadata (GDP, life expectancy, population)
```
---
📊 Visualizations Included
Chart	Description
🗺️ World Map	Choropleth showing % of health facilities with limited hygiene by country
📊 Bar Chart	Top 10 worst-affected countries
🔵 Scatter Plot	GDP per capita vs. hygiene gap with regression line
📈 Time Series	Global average trend over available years
---
🛠️ Tools & Technologies
Python — Data processing and visualization
pandas — Data manipulation
geopandas — Geospatial data for world map
plotnine — ggplot2-style visualizations
Quarto — Report rendering to HTML
CSS — Custom styling for the HTML report
---
How to Run
Prerequisites
Python 3.10+
Quarto installed
Required Python packages:
```bash
pip install pandas geopandas plotnine
```
Render the Report
```bash
quarto render report.ipynb --execute
```
Or using R:
```r
library(quarto)
quarto_render("report.ipynb", execute = TRUE)
```
This generates `report.html` which can be opened in any browser.
---
📂 Data Sources
UNICEF Global Databases — Health facility hygiene indicators
World Bank Development Indicators — GDP per capita, life expectancy, population data
---
🔍 Key Findings
Countries across Sub-Saharan Africa and parts of South Asia show the highest proportions of health facilities with limited hygiene
A clear negative correlation exists between GDP per capita and poor hygiene in health facilities
Progress has been slow and uneven — for the most vulnerable countries, the pace of change is not fast enough
Access to hygienic healthcare remains a privilege, not a universal right
---
👩‍💻 Author
Additi Mohanty
---
📄 License
This project is for academic purposes. Data belongs to their respective sources (UNICEF, World Bank).
