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
 - `DAY_2/` — Notebooks for Day 2 practice:
  - `Abstraction.ipynb`
  - `classes_objects.ipynb`
  - `Encapsulation.ipynb`
  - `functions_practice.ipynb`
  - `Inheritance.ipynb`
  - `Polymorphism.ipynb`
 - `DAY_3/` — Notebooks for Day 3 practice:
  - `Numpy.ipynb`

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
- `Abstraction.ipynb` — conceptual overview of abstraction in OOP.
- `classes_objects.ipynb` — creating and using classes and instances.
- `Encapsulation.ipynb` — access control and data hiding examples.
- `functions_practice.ipynb` — extra function exercises and drills.
- `Inheritance.ipynb` — subclassing and method reuse.
- `Polymorphism.ipynb` — polymorphic behavior and duck typing.
- `Numpy.ipynb` — basic NumPy array operations and examples.

## Notes / Next Steps

- Add `requirements.txt` if you rely on third-party libraries.
- Track progress by creating new DAY_N folders for subsequent lessons.

---
Happy coding! Keep experiments small and iterate often.
