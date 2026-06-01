# COVID Public Health Dashboard

Public health analytics project focused on case trends, positivity, vaccination, hospitalizations, and regional monitoring.

## Business Questions

- Which regions show rising case trends?
- How do vaccination and hospitalization rates compare?
- Where should public health teams focus?
- What metrics should appear in a dashboard?

## Repository Structure

```text
data/                 Sample data for the case study
src/                  Python analysis workflow
sql/                  SQL queries for KPI extraction
reports/              Executive summary and recommendations
outputs/              Generated analysis outputs, ignored by git
requirements.txt      Python dependencies
```

## How To Run

```bash
pip install -r requirements.txt
python src/analysis.py
```

The script reads `data/sample_data.csv`, creates KPI summaries, and saves generated outputs in `outputs/`.

## Analyst Skills Demonstrated

- Cleaning and profiling a structured dataset
- Creating KPI summaries with Python
- Writing SQL-style business questions
- Translating metrics into executive recommendations
- Organizing a reproducible portfolio repository
