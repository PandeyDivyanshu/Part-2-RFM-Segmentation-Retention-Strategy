# Part 2 - RFM Segmentation & Retention Strategy

This repository builds customer segments using RFM plus additional behavioral signals.

## Required outputs included

- `rfm_segmentation.ipynb`
- `segments.csv` (generated/refreshed by notebook)
- `retention_strategy.md`
- `manual_review_cases.md`
- `requirements.txt`

## Setup

```bash
python -m venv .venv
.venv\\Scripts\\activate
pip install -r requirements.txt
```

## Data

Place assignment CSV files inside `data/`.

## Run

1. Open `rfm_segmentation.ipynb`.
2. Run all cells.
3. Confirm `segments.csv` is created/updated.
4. Refresh narrative sections in markdown reports using generated evidence.

