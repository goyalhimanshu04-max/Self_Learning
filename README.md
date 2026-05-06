# SELF_LEARNING

A personal collection of Python learning notes, practice notebooks, and small projects.

This repository organizes progressive learning material by day and topic. Notebooks contain examples, exercises, and short experiments you can run interactively.

**Quick links**
- Notebooks: `DAY_1/` .. `DAY_6/`
- Data: `data/`
- Generated outputs: `artifacts/`

**Prerequisites**
- Python 3.8+
- Recommended: a virtual environment (`venv` or `virtualenv`)
- Jupyter (`notebook` or `jupyterlab`)

## Setup
1. Create and activate a virtual environment.

Windows (PowerShell):
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

macOS / Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies (if present):
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

3. Run Jupyter and open notebooks:
```bash
jupyter notebook
# or
jupyter lab
```

## Recommended workflow
- Keep code and small data samples in the repository.
- Store large or sensitive data outside the repo; use `artifacts/` for generated outputs.
- Use `requirements.txt` to pin dependencies for reproducibility.

## Project structure (high-level)
- `DAY_1/` .. `DAY_6/` — learning notebooks, organized by day/topic.
- `data/` — small sample datasets used by notebooks (small CSVs are OK to track).
- `artifacts/` — generated outputs, models, plots (ignored by git).

## Suggested next steps
- Add `requirements.txt` with the libraries you use.
- Add short README sections inside each `DAY_N` folder describing what to run.


