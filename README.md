@'
# Mexican Banking Financial Performance & Risk Dashboard

End-to-end financial analysis and business intelligence project using real data from Mexican financial and economic institutions.

## Overview

This project develops a reproducible financial analysis workflow focused on the Mexican multiple banking sector.

The objective is to integrate real financial institution data with relevant macroeconomic indicators, transform the information into an analytical database, and build financial models and business intelligence dashboards.

## Business Problem

Financial institutions generate large volumes of financial and economic information that must be transformed into meaningful indicators for analysis and decision-making.

This project aims to build a structured workflow capable of:

- Integrating financial and macroeconomic data.
- Monitoring banking-sector performance.
- Analyzing credit portfolio composition and growth.
- Examining profitability and risk indicators.
- Providing interactive analytical views through Excel and Power BI.

## Objectives

- Obtain and document real data from reliable institutional sources.
- Develop a reproducible data extraction and cleaning process.
- Design a relational SQL database for analytical purposes.
- Perform financial and statistical analysis.
- Develop an Excel financial analysis model.
- Automate recurring Excel processes using VBA.
- Build an interactive Power BI dashboard.
- Validate consistency between the different analytical layers.
- Document the complete workflow for reproducibility.

## Data Sources

The project will use official and reliable sources, primarily:

- Comision Nacional Bancaria y de Valores (CNBV)
- Banco de Mexico (Banxico)

Specific datasets, variables, frequencies, periods, formats, and access methods will be documented during the data acquisition phase.

## Technology Stack

- Python
- pandas
- SQL
- PostgreSQL
- Microsoft Excel
- VBA
- Power BI
- DAX
- Git
- GitHub
- Visual Studio Code

## Project Architecture

```text
Real Data
    |
    +-- CNBV
    |
    +-- Banxico
         |
         v
Python Extraction & Cleaning
         |
         v
SQL Database
      /     \
     v       v
  Excel   Power BI
   + VBA    + DAX
     \       /
      \     /
       v   v
Financial Analysis & Dashboards
```

## Project Status

Currently in the project setup phase.

The repository structure, Git workflow, and GitHub repository have been initialized. Data acquisition and analytical development will be completed incrementally.

## Repository Structure
mexican-banking-financial-dashboard/
|
+-- data/
|   +-- raw/
|   +-- processed/
|
+-- python/
|   +-- extraction/
|   +-- cleaning/
|   +-- validation/
|
+-- sql/
|   +-- schema/
|   +-- staging/
|   +-- queries/
|   +-- views/
|
+-- excel/
+-- vba/
+-- powerbi/
|
+-- docs/
|   +-- architecture/
|   +-- data_dictionary/
|   +-- methodology/
|   +-- screenshots/
|
+-- tests/
|
+-- README.md
+-- .gitignore

## Disclaimer

This repository is an educational and professional portfolio project. Analytical results will be based on publicly available data and documented methodologies.

## Author: Eduardo Ponce
## Field: Actuarial Science
'@ | Set-Content README.md -Encoding utf8