# Data Pipeline

This folder contains the Python data processing pipeline for the UNFPA CSE Dashboard.

## Files

| File | Purpose |
|------|---------|
| `collect_and_process.py` | Main Python script — loads, cleans, analyzes data and generates JavaScript output |
| `raw_indicators.csv` | Raw indicator data (auto-generated sample if not present) |
| `dashboard_data.js` | Generated JavaScript data file (output from the script) |

## Running the Pipeline

```bash
cd data
python collect_and_process.py
```

## Pipeline Stages

1. **Load** — Reads raw indicator CSV
2. **Clean** — Validates ranges, handles missing values, converts types
3. **Analyze** — Computes regional averages, Pearson correlations
4. **Trends** — Generates historical time series data
5. **Output** — Writes embeddable JavaScript for the dashboard

## Data Sources

Indicator values are compiled from:
- WHO Global Health Observatory
- UNFPA State of World Population
- UNAIDS
- World Bank Open Data
- UNESCO Institute for Statistics
