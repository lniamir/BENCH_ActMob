# BENCH_ActMob (Active Mobility)

## Model Specifications
* **Paper Name:** [Urban Strategies for Active Mobility in Vienna](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6604470)
* **Journal / Medium:** SSRN
* **Year:** 2026
* **Authors:** Áron Dénes Hartvig, Leila Niamir
* **Calibration Area:** Vienna
* **Code DOI:** [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20847261-blue)](https://doi.org/10.5281/zenodo.20847261)

## Technical Stack & Environment
* **Language:** Python
* **Framework:** Mesa Agent-Based Modeling Framework
* **Environment Manager:** `uv`

## Installation & Execution via `uv`

This model utilizes `uv` workspace management. If you don't have `uv` installed, it is a fast, modern Python package and environment manager that replaces `pip` and `poetry` (install it via `curl -LsSf https://astral.sh/uv/install.sh` or `brew install uv`).

To sync the locked project state and execute the simulation, run the following commands in this directory:

```bash
# Automatically install uv (if not present), create .venv, and sync exact dependencies from uv.lock
uv sync

# Execute the simulation entrypoint using the locked environment
uv run python run_BENCH_Mobility.py
```