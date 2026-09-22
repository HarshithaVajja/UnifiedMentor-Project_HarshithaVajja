# Business Analyst Internship Projects — Unified Mentor

Two BI dashboard projects completed during a Business Analyst internship 
at Unified Mentor, covering ESG data governance (Power BI) and supply 
chain operations (Tableau).

## Overview
Built two interactive dashboards translating raw multi-source datasets 
into decision-ready visuals: one tracking ESG (Environmental, Social, 
Governance) metrics across countries using World Bank data, and one 
surfacing inventory, supplier, and shipping performance for a fashion/
beauty startup's supply chain.

## Tech Stack
- Power BI Desktop (Power Query, DAX)
- Tableau Public Desktop
- Excel

## Project 1: Data Governance & Security Dashboard (Power BI)
- **Dataset:** World Bank ESG data (ESGData, ESGCountry, ESGSeries — 
  metric values, country codes, and series descriptions)
- **Approach:** Unpivoted and typed the raw data in Power Query, built 
  relationships between country/series tables, added DAX measures for 
  total and average ESG value
- **Features:** Geographic map of ESG distribution, KPI cards, dynamic 
  filtering by country and metric

## Project 2: Supply Chain Management Dashboard (Tableau)
- **Dataset:** `supply_chain_data.csv` (100 rows, 24 columns — SKU, 
  order quantity, shipping time, supplier, costs, defect rate)
- **Approach:** Built calculated fields (e.g. total cost = manufacturing 
  + shipping), used tiled layout with interactive filters/legends
- **Findings:** Road transport was the slowest shipping method, air the 
  fastest; supplier performance varied notably on defect rate and delay; 
  costs varied significantly by product type

## Files
- `UM-project_HarshithaVajja.pdf` — full project report with dashboard 
  screenshots and methodology

