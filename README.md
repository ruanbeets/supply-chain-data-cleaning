# Supply Chain Data Cleaning

## Objective
Clean and standardize a large supply-chain dataset and produce a small set of delivery performance KPIs suitable for reporting and dashboards.

## Dataset
Public supply-chain dataset (DataCo).
~90MB raw CSV with data quality issues typical of ERP exports.

## Work Performed
- Data audit and validation
- Deduplication and standardization
- Date normalization and derived lead-time metrics
- KPI snapshot with summary tables and charts

## Outputs
- Cleaned, analysis-ready dataset
- KPI summary tables
- Executive summary highlighting key findings

## Tools
Python, pandas, Excel

## Environment Setup

```bash
python3 -m venv .venv
source .venv/bin/activate.fish
pip install -r requirements.txt


## Notes
This project is designed to mirror a real client data-cleaning engagement. Column definitions were referenced from the original dataset documentation to ensure correct interpretation of dates, quantities, and delivery fields.
