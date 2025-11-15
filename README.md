
# Afyaledger

Repository containing Afyaledger datasets, notebooks and scripts.

## Contents
- Afyaledger-v1.ipynb : Model training notebook (fusion model)
- Afyaledger-feature-pipeline.ipynb : Quant feature engineering pipeline
- data/ : place your CSV datasets here (companies.csv, income_statements.csv, ...)
- models/ : saved models and artifacts
- requirements.txt : python dependencies

## How to run
1. Place the provided CSVs in `data/` or set DATA_DIR appropriately in the notebooks.
2. Create a Python environment and install requirements (see requirements.txt).
3. Run `Afyaledger-feature-pipeline.ipynb` to generate engineered features.
4. Run `Afyaledger-v1.ipynb` to train the model.

