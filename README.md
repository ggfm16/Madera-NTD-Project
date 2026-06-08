# START HERE
# Madera Transit Analysis-Ralph Cuevas

Analyzes 10 years of City of Madera transit data using a Python ETL pipeline across 70+ NTD Excel files. Includes QGIS geospatial visualizations using GTFS and 2020 census data, an interactive Excel dashboard, and findings on transit efficiency, ridership trends, and thoughts on HSR readiness.

---

## Where to Start

| What you want | Where to go |
|---|---|
| A quick overview of findings and visualizations | Slide Deck |
| Full methodology and design decisions | Madera NTD Project Methodology.md |
| Interactive live map of Madera's routes and population | Live Madera Map.md |

---

## Repository Contents

**Slide Deck** — A self-contained PowerPoint presentation summarizing the project's visualizations and key findings. Start here if you want the TLDR. A Public Google Sheets link is included in the folder for ease of access.

**Live Madera Map.md** — Contains a link to an online hosted version of the QGIS route and population map. No software required to view it. Mobile friendly.

**Madera NTD Project Methodology.md** — The full methodology document covering the ETL pipeline, QGIS visualization design, Excel dashboard architecture, and key findings.

**NTD Project** — The raw NTD Excel files organized by year used as input to the ETL pipeline DO NOT RENAME FOLDER OR FILES.

**Python ETL** — Contains the ETL pipeline notebook, and the CSV output, refer to the methodology file for details on running yourself.

**Project Excel Sheet** — The interactive Excel dashboard built from the CSV output. Download and open in Excel to access the full slicer and conditional formatting functionality — these features do not render in browser preview. Incompatible with Google Sheets.

**QGIS Project File** — The QGIS project file containing all map layers, styling, and labeling configuration. Requires QGIS to open.
