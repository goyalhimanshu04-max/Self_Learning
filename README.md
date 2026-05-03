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

## Learning Journey

This repository follows a progressive learning path from Python fundamentals up through production-ready machine learning operations (MLOps) and large‑language-model operations (LLMOps). The stages below describe recommended topics and practical milestones.

- **Basics:** Python syntax, data types, control flow (`if`/`else`), functions, and basic I/O. (Covered in `DAY_1` notebooks.)
- **Intermediate:** Data structures, error handling, modules/packages, file handling, and unit testing. Start building small projects and reusable functions.
- **Object-Oriented Programming:** Classes, objects, encapsulation, inheritance, and polymorphism (see `DAY_2` notebooks).
- **Data & Scientific Computing:** Working with `NumPy`, `pandas`, and data visualization (`matplotlib`, `seaborn`) for exploratory data analysis.
- **Machine Learning Basics:** Supervised/unsupervised learning, model evaluation, and `scikit-learn` workflows. Practice end-to-end experiments and reproducible notebooks.
- **Deep Learning & LLMs:** Intro to neural networks, PyTorch/TensorFlow basics, training pipelines, and experimenting with transformer models and prompt engineering.
- **MLOps (Advanced):** Containerization (Docker), experiment tracking, CI/CD for models, model versioning, feature stores, scheduling and orchestration (Airflow/Kubeflow), scalable training and inference, monitoring, and logging.
- **LLMOps (Advanced):** Deployment and serving of LLMs, prompt/version management, infrastructure for fine-tuning and inference at scale, safety and alignment checks, cost monitoring, and evaluation pipelines.

Suggested next steps: add `requirements.txt` (done), create sample end-to-end notebooks showing dataset → model → deployment, and add a small checklist for reproducible experiments.

## Notes / Next Steps

- Add `requirements.txt` if you rely on third-party libraries.
- Track progress by creating new DAY_N folders for subsequent lessons.

---
Happy coding! Keep experiments small and iterate often.
