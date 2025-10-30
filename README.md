# Flight Delay Prediction (Part A & Part B)

This repo contains two notebooks and minimal environment files for reproducing a binary classification workflow on US flight delays.

## Files
- `PartA.ipynb` — Data prep, feature engineering (holidays + weather), baseline logistic model, evaluation.
- `PartB.ipynb` — Cloud/Part B work: train/valid/test splits (70/15/15), Linear Learner/XGBoost (local-friendly), metrics, ROC/CM plots.
- `requirements.txt` — Python packages.
- `environment.yml` — Conda environment (optional).
- `.gitignore` — Ignore checkpoints and temp files.

## How to run (local)
```bash
python -m venv .venv && source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
jupyter lab

