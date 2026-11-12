# Retail Sales ETL Practice

A learning project where I build ETL (Extract, Transform, Load) pipelines
with Python, SQL. It uses LA retail sales data to practice the full flow from raw files to analysis-ready tables.

## What this project covers

- **Extract:** reading data from [CSV / JSON / JSON Lines / database / API / Parquet]
- **Transform:** cleaning, type conversion, handling nulls and duplicates,
  combining multiple files, feature engineering
- **Load:** writing the cleaned data to [SQLite / PostgreSQL / MySQL / CSV]
- **Analyze:** SQL queries and [Power BI / Tableau / notebooks] on the result

## Tech stack

| Area | Tools |
|---|---|
| Language | Python 3.x |
| Libraries | pandas, [SQLAlchemy, etc.] |
| Database | sqlite |
| Other | [Airflow / Power BI / ...] |


## Data

- **Source:** LA Retail Sales dataset
- **Formats used:** [JSON, CSV, ...]

## How to run

```bash
git clone [repo-url]
cd [repo-name]
pip install -r requirements.txt
python src/[main_script].py
```

## Key learnings

- Combining many files with a single `pd.concat` on a list instead of
  concatenating inside a loop
- Handling different JSON layouts (`lines=True` for JSON Lines, `json_normalize`
  for nested data)

## Author

Akshay · [LinkedIn / GitHub links]