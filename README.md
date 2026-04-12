# Energy Demand Analysis — Big Data Analytics Project

## Yenepoya (Deemed To Be University)
### BCA — Data Science, Big Data Analytics

---

## Project Overview
This project demonstrates a complete Big Data ETL pipeline on a 
real-world European energy dataset. We analyze historical hourly 
energy demand patterns across 2015–2018 using Python, Pandas, 
SQL and Tableau.

---

## Technologies Used
- Python 3.x
- Pandas
- SQLite3
- Matplotlib
- Jupyter Notebook
- Tableau Desktop

---

## Dataset
- Source: ENTSO-E European Energy Grid
- Records: 35,064 hourly readings
- Period: January 2015 to December 2018
- Columns: 29 (generation sources, load, forecasts, prices)

---

## ETL Pipeline
- **Extract** — Load raw CSV using pandas.read_csv()
- **Transform** — GroupBy aggregations simulating MapReduce
- **Load** — Store results in SQLite database + CSV export

---

## Key Findings
1. Peak energy demand occurs at Hour 11 (11am) daily
2. July has the highest monthly average energy demand
3. Energy demand grew steadily from 28,358 MW (2015) to 29,064 MW (2018)
4. Renewable and Fossil generation are nearly equal across all months
5. Strong positive correlation between energy demand and market price

---
## Project Structure

    Energy-Demand-Analysis/
    │
    ├── README.md
    ├── project.ipynb
    ├── energy_dataset.csv
    │
    ├── outputs/
    │   ├── hourly_energy.csv
    │   ├── monthly_energy.csv
    │   ├── daily_energy.csv
    │   ├── yearly_energy.csv
    │   ├── renewable_vs_fossil.csv
    │   └── price_vs_demand.csv
    │
    ├── dashboard/
    │   └── energy_dashboard_final.twb
    │
    └── docs/
        ├── Energy_Demand_LLD.docx
        └── Energy_Demand_HLD.docx
