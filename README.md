# Walmart End-to-End Analytics Project

![Project Pipeline](walmart_project-piplelines.png)

## Overview

This repository demonstrates an end-to-end analytics workflow on Walmart sales data: data ingestion, cleaning, exploratory data analysis (EDA), SQL querying, and example visualizations.

## Files in this repo

- Walmart.csv — original dataset (CSV)
- walmart_clean_data.csv — cleaned dataset used for analysis
- project.ipynb — Jupyter notebook containing EDA, cleaning, and charts
- MySQL Queries.sql — example MySQL queries
- PSQL Queries.sql — example PostgreSQL queries
- requirements.txt — Python dependencies

## Quick start

1. Create and activate a virtual environment:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1  # Windows PowerShell
# or: .venv\Scripts\activate.bat  # Windows CMD
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open `project.ipynb` in Jupyter Lab/Notebook and run the cells.

## Usage notes

- Use `walmart_clean_data.csv` for quicker iteration; it contains cleaned and typed data.
- The SQL files show example queries and can be run against a local MySQL/Postgres instance (adjust connection settings as needed).
- If you plan to re-download data from Kaggle, follow the Kaggle API steps (store `kaggle.json` in `~/.kaggle`).

## Requirements

- Python 3.8+
- See `requirements.txt` for package versions used in the notebook.

## Next steps (suggested)

- Commit any analysis scripts you add and keep `project.ipynb` runnable end-to-end.
- Add a `data/` folder and a `.gitignore` entry if you intend to avoid committing large raw datasets.

## License & Contact

This repository currently has no specific license file. Open an issue or pull request if you'd like to add one or contribute.

---

_Updated: February 2026_
