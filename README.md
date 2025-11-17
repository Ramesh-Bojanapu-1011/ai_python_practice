# AI Python Practice

This repository provides short, hands-on examples for classical machine
learning tasks implemented as Jupyter notebooks and small demo scripts.

## Quickstart

-> Create and activate a virtual environment (Windows PowerShell):

```powershell
python -m venv .Venv
& .Venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

-> Launch Jupyter Lab to run and edit the notebooks interactively:

```powershell
jupyter lab
```

## Notes

- Many notebook cells call `model.predict(...)` and expect inputs with the
  same column names used during training. To avoid scikit-learn warnings
  such as "X does not have valid feature names", pass a `pandas.DataFrame`
  with matching column names (examples are included in the notebooks).

- Excel support: this project uses `openpyxl` for `pandas.read_excel()`;
  a compatible version (`openpyxl==3.1.5`) is available in `requirements.txt`.
