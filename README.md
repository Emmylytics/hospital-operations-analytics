# hospital-operations-analytics
## Problem Statement

Hospitals often face inefficiencies in patient flow and variability in patient length of stay (LOS), which can affect operational performance and service delivery.
Understanding trends and factors that influence LOS is essential for monitoring performance and optimizing patient flow.

## Project Overview
This project implements an end-to-end analytics workflow to explore hospital admissions, patient LOS, and patterns in medical conditions.
The goal is to produce actionable insights that help monitor hospital performance and support operational decision-making.

## Dataset Overview
Hospital admission and discharge records include:
- Patient ID
- Admission Date / Discharge Date
- Medical Condition
- Billing Amount
- Admission Type

## Key Objectives
- Analyze trends in hospital admissions over time
- Evaluate LOS by age group and medical condition
- Examine patterns in emergency vs elective admissions
- Identify factors influencing patient stay duration to support operational improvements
Design dashboard layout and prototype Build interactive dashboards and KPI visualizations 
## Tech Stack & Workflow

| Phase                        | Tool / Language        | Description                                         |
|-------------------------------|----------------------|---------------------------------------------------|
| Data Cleaning & Preprocessing | Python (Pandas, NumPy)| Clean raw data, standardize fields, calculate LOS|
| Exploratory Data Analysis (EDA)| SQL                  | Aggregate, segment, and summarize key operational metrics |
| Wireframing                    | Figma                | Design dashboard layout and prototype |
| Visualization & Dashboard      | Power BI             | Build interactive dashboards and KPI visualizations            |

## Key Insights
- Admissions peaked 2020–2023, with a slight decline in 2024
- Senior and Elderly patients tend to have longer LOS → opportunity for monitoring and operational planning
- Emergency vs elective vs urgent admissions are almost evenly split
- Certain medical conditions correlate with longer LOS, highlighting patterns for performance tracking

## Repository Structure

```
hospital-analytics/
├─ data/
│  └─ healthcare_dataset.csv
├─ python/
│  └─ preprocessing.ipynb
├─ sql/
│  └─ eda_queries.sql
├─ powerbi/
│  └─ dashboard.pbix
├─ assets/
│  └─ dashboard_preview.png
└─ README.md
```
