# Telecom Churn & Revenue Dashboard

**WGU MSDA D210 | Jared Medlin | March 2025**

## Overview

An interactive Tableau dashboard comparing churn rate and Average Revenue 
Per User (ARPU) between a telecom company and a competitor dataset, 
with state-level and phone plan filtering. Accompanied by a recorded 
presentation tailored for a technical data analyst audience.

## Key Findings

- Company monthly charges were notably higher than the competitor,
  a likely contributor to elevated churn rates
- Churn rate vs competitor varied meaningfully by state, suggesting 
  regional factors beyond pricing are involved
- Customers without a phone plan showed different churn and pricing 
  patterns than those with one

## Dashboard Features

- Churn rate comparison between company and competitor (bar chart)
- ARPU comparison across both datasets
- Monthly charge distribution (histogram) for both datasets
- Filter by state (multi-select) and phone plan status

## How to Open

1. Download and install [Tableau Desktop](https://www.tableau.com/products/desktop)
   or [Tableau Public](https://public.tableau.com/app/discover) (free)
2. Place `D210.twb`, `churn_clean.csv`, and `churn-bigml-20.csv` 
   in the **same folder**
3. Open `D210.twb` in Tableau — if prompted, point it to the CSV files
4. Use the filters on the right to explore by state or phone plan
5. Press **F7** for presentation mode

## Presentation

[Video walkthrough (Panopto)](https://wgu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=56d74bb5-e8cb-4680-9117-b2a300b836e2)

## Tools Used

- Tableau Desktop
- Colorblind-safe palette design

## Data Sources

- Internal telecom dataset (`churn_clean.csv`)
- [Competitor dataset](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets)
  (`churn-bigml-20.csv`) — Kaggle

## Repository Contents

| File | Description |
|------|-------------|
| `D210.twb` | Tableau workbook (requires CSVs in same folder) |
| `churn_clean.csv` | Primary telecom customer dataset |
| `churn-bigml-20.csv` | Competitor comparison dataset |
