# India-General-Election-Result-Analysis-2024

This repository documents an end-to-end data analytics project focused on the **2024 Indian General Elections**, leveraging five relational datasets for comprehensive data modeling, SQL analysis, and rich Power BI dashboarding.


## 🔍 Project Overview

This project demonstrates the **use of multiple, related datasets to analyze the 2024 Indian General Elections** with both SQL and Power BI. All data import, transformation, and visualization are built using the five datasets listed above — ensuring consistency across SQL analysis and dashboard reporting.

### Key Features
- **Multi-table Data Modeling:** Complex joins for state, party, and constituency-level reporting.
- **SQL Analysis:** Robust scripts for cleaning, aggregating, and deriving insights from all tables.
- **Power BI Dashboards:** Interactive visualizations, all sourced from these datasets.

## 🗂️ Data Sources

| Dataset                    | Description                                                    |
|----------------------------|----------------------------------------------------------------|
| constituencywise_details   | Candidate/candidate party details for each constituency        |
| constituencywise_results   | Result metrics (votes, margins, winner/runner-up, etc.)        |
| partywise_results          | Party-wise performance by state                                |
| states                     | State names, codes, and geospatial codes                      |
| statewise_results          | Aggregated KPIs per state (turnout, EVM/postal split, etc.)    |

These files were imported as CSVs and joined for analysis. No direct SQL database backend was used in the Power BI dashboard, but all merges and relationships were implemented inside Power BI’s data model.

##  Dashboard Highlights

### 1. Landing Page
- **Navigation cards** for easy dashboard access (Overview, State Demographics, Political Landscape, Constituency Analysis)

### 2. Overview Analysis
- Alliance-wise seat/vote breakdown (NDA, I.N.D.I.A., Others)
- KPI grids and party-wise seat breakdowns

### 3. State Demographic Analysis
- State-level maps of seat shares, majority alliances, and party performance
- Drill-down bubble maps for constituency-level visualization

### 4. Political Landscape by State
- Selectable state view with KPIs for each alliance and party
- Seat share visualizations and sortable grids

### 5. Constituency Analysis
- Deep dive: total votes, EVM vs postal votes, candidate performance, top three rankings
- View by seat margin, candidate, or party

### 6. Details Grid
- All results, fully filterable, exportable for analyst use
- Includes drill-through capability and Excel export

## ⚙️ Data Workflow

1. **Import:** All five datasets imported as CSVs into Power BI.
2. **Modeling:** Relationships established using Power BI’s data model (star/snowflake schema as needed).
3. **SQL Analysis:** Sample queries included in `SQL-Queries.docx` for learners wishing to practice independent data wrangling or to replicate logic outside Power BI.
4. **Visualization:** All reporting, analysis, and KPIs in Power BI reference this unified data foundation.

## 🖼️ Sample Dashboard Images

**Landing Page:**  
<img width="1372" height="750" alt="Screenshot 2025-08-02 035245" src="https://github.com/user-attachments/assets/2f161e5c-1185-4631-8a62-90ea2b7eb182" />


**Overview Analysis:** 

<img width="1297" height="724" alt="Screenshot 2025-08-02 035541" src="https://github.com/user-attachments/assets/41b1a012-b977-4a0f-9319-a17a5a09a63b" />
<img width="1297" height="721" alt="Screenshot 2025-08-02 035526" src="https://github.com/user-attachments/assets/84cf3eef-42ec-4961-8be0-f329ba842044" />



**State Demographics:** 
<img width="1294" height="714" alt="Screenshot 2025-08-02 035630" src="https://github.com/user-attachments/assets/f43a3e54-edc9-4074-8434-986657351a72" />



**Political Landscape by State:**

<img width="1296" height="709" alt="Screenshot 2025-08-02 035700" src="https://github.com/user-attachments/assets/4d271998-0004-41f0-90b6-03406955b8c1" />



**Constituency Analysis:** 
<img width="1284" height="714" alt="Screenshot 2025-08-02 035725" src="https://github.com/user-attachments/assets/68fa3e97-d3b1-4fe5-8e70-85c94c07c063" />







  


## 📝 How to Use

- **Power BI:** Open the `.pbix` file; dashboards will load off the five imported datasets.
- **SQL:** Review/run scripts in `SQL-Queries.docx` after importing each CSV as its own table in SQL.
- **Screenshots:** Browse `/screenshots/` for a quick preview.

### For Recruiters/Hiring Managers
- Demonstrates advanced data modeling from multiple sources
- Shows competence in both SQL analytics and Power BI dashboarding
- Fully reproducible with only CSVs and Power BI Desktop


