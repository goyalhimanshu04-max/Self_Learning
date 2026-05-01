# SELF_LEARNING

Personal Python learning notes and practice notebooks.

## Overview

This repository contains interactive Jupyter notebooks and exercises for learning core Python concepts. The notes are organized by day and topic to track progress and practice coding patterns.

## Structure

- `DAY_1/` — Notebooks for Day 1 practice:
  - `control_statements.ipynb`
  - `functions.ipynb`
  - `loops.ipynb`
  - `pattern_questions.ipynb`

## Prerequisites

- Python 3.8 or newer
- (Optional) `virtualenv` or `venv`
- Jupyter support (`notebook` or `jupyterlab`)

## Setup

Create and activate a virtual environment, then install any needed packages:

Windows (PowerShell):
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install jupyter
```

macOS / Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyter
```

If you add dependencies later, create a `requirements.txt` and install with:
```bash
pip install -r requirements.txt
```

## Usage

- Open the repository in VS Code or another editor with Jupyter support.
- Launch notebooks with `jupyter notebook` or `jupyter lab` and run cells interactively.

## Notebooks

- `control_statements.ipynb` — if/else examples and branching logic.
- `functions.ipynb` — function definitions, parameters, return values.
- `loops.ipynb` — `for`/`while` loops and iteration patterns.
- `pattern_questions.ipynb` — small algorithmic and pattern-printing exercises.

## Notes / Next Steps

- Add `requirements.txt` if you rely on third-party libraries.
- Track progress by creating new DAY_N folders for subsequent lessons.

---
Happy coding! Keep experiments small and iterate often.
