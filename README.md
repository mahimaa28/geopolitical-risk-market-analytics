# geopolitical-risk-and-market-analytics

## Overview
Analysis of how the Geopolitical Risk (GPR) Index relates to US inflation, S&P 500 returns, and oil prices across 40 years(1985-2024) of monthly data.

## Key Findings
- GPR is a leading indicator of CPI inflation with peak predictive power at a 6-month lag.
- Stock markets show measurable abnormal return in the months following geopolitical shocks.
- Oil prices mediate a significant portion of the GPR -> inflation relationship.

## Tech Stack
Python (Pandas, NumPy, Plotly, Matplotlib, SciPy), SQL (SQLite), Tableau

## Data Sources
- GPR Index: Caldara & Iacoviello (2022)
- CPI Inflation: FRED (CPIAUCSL)
- S&P 500: Yahoo Finance
- WTI Oil: FRED (DCOILWTICO)

## Project Structure
- `gpranalysis.ipynb` : Main analysis notebook
- `master_dataset.csv` : Cleaned unified dataset
- `tableau_data.csv` : Tableau-ready export

## How to Run 
Open `gpranalysis.ipynb` in Google Colab and run all cells.
Upload GPR Excel file(gpr_monthly) when prompted.



