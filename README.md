# AI Python Practice

This repository contains small hands-on examples for classical supervised
and unsupervised machine learning tasks written as notebooks and short
demo scripts.

Contents

- `Supervised_Learning/Classification/` — notebooks and scripts demonstrating
 binary and multi-class classification (KNN, Logistic Regression, etc.).
- `Supervised_Learning/Regression/` — regression examples (linear, polynomial).
- `Un_Supervised_Learning/` — examples for clustering and dimensionality reduction.

Quickstart

-> Create and activate the virtual environment (Windows PowerShell):

```powershell
python -m venv .venv
& .venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

-> Open and run the notebooks with Jupyter Lab / Notebook:

```powershell
python -m notebook
```

Notes

- Many notebook cells call `model.predict(...)` and expect inputs with the
 same column names used during training. To avoid scikit-learn warnings like
 "X does not have valid feature names", pass a `pandas.DataFrame` with
 matching column names (examples in the notebooks).

Contributing

- Feel free to add examples or improve documentation. Keep changes small
 and focused; update `requirements.txt` if you add new dependencies.

License

- No license specified. Add a LICENSE file if you intend to open-source this repo.
