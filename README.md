# Healthcare Provider Dashboard

Power BI dashboard analyzing UK healthcare provider financial performance across 5000+ patient visits and 8 datasets.

## Overview

Financial analysis dashboard built to optimize departmental revenue and operational efficiency. Processes patient visits, provider performance, billing, and insurance data across UK healthcare facilities.

## Key Metrics

- Total billing amount: £377K across all departments
- Average billing per visit: £636.31
- Top performing departments: Cardiology (30.8%), General Surgery (30.4%)
- Geographic coverage: Major UK cities including Birmingham, Glasgow, Manchester
- Insurance vs out-of-pocket analysis by service type

## Technical Implementation

**Data Sources:**
- 8 CSV datasets: cities, departments, diagnoses, insurance, patients, procedures, providers, visits
- 5000+ patient visit records
- Multi-table relationships established via Power Query

**ETL Pipeline:**
- Power Query for data extraction and transformation
- Automated data validation and cleaning
- Calculated columns for KPI metrics

**Dashboard Features:**
- Interactive filtering by city/state
- Collapsible slicer panel activated by "Open Filter" button
- Demographic filters (Patient Race: Asian, Black, Hispanic, White, Other)
- Time-based filtering (Year, Quarter, Month with 2024/2025 data)
- Dual theme support (light/dark mode)
- Geographic visualization with UK map
- Department performance comparison
- Procedure and diagnosis breakdown by service type
- Drill-down capabilities for detailed analysis

## Dashboard Views

### Light Theme
![Light Mode](https://github.com/user-attachments/assets/c2866965-b47a-43f2-a8e5-220eefb375f4)


### Dark Theme  
![Dark Mode](https://github.com/user-attachments/assets/37217d8c-a147-4d36-a947-ec59b826c5b7)


## DAX Calculations

Key measures implemented:
- Average billing amount per visit
- Department revenue percentage
- Insurance coverage ratios
- Geographic distribution metrics
- Service type analysis (Emergency/Inpatient/Outpatient)

## Files Structure

```
├── data/
│   ├── cities.csv
│   ├── departments.csv
│   ├── diagnoses.csv
│   ├── insurance.csv
│   ├── patients.csv
│   ├── procedures.csv
│   ├── providers.csv
│   └── visits.csv
├── Healthcare_Dashboard.pbix
└── README.md
```

## Installation

1. Download Power BI Desktop
2. Clone repository
3. Open Healthcare_Dashboard.pbix
4. Refresh data sources if needed

## Skills Demonstrated

- Power BI dashboard development
- DAX calculations and measures
- Power Query ETL processes
- Healthcare data analysis
- Financial performance metrics
- Geographic data visualization
