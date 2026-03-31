# GradSingapore-Survey-Data-Analytics
We analysed a dataset of over 2500 entries on university students’ perceptions of employers provided by GradSingapore. We performed end-to-end data analysis, including data cleaning, transformation, and statistical modelling, to derive actionable insights.


#README

## 1) Contents
This folder includes:
- **Submission Notebook**: `Data Analysis code.ipynb` (main code)
- **Requirements File**: `requirements.txt` (Python dependencies)
- **README File**: `README.md` (this file)
- **Statistics Report**: `Survey Data Analysis Report`

## 2) Environment Setup (Windows / macOS / Linux)
We recommend creating a fresh virtual environment.

### use venv
```bash
# from your submission folder
python -m venv .venv

# activate
# Windows (PowerShell)
.venv\Scripts\Activate.ps1
# Windows (cmd)
.venv\Scripts\activate.bat
# macOS/Linux
source .venv/bin/activate

# install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## 3) Data Setup
This notebook expects the datathon dataset file (Excel `.xlsx`).

1. Create a folder `data/` in the submission directory.
2. Place the dataset inside `data/` (example name: `sds_datathon_gradsingapore.xlsx`).
3. In the notebook, update the dataset path variable (look for `DATA_PATH = ...`) to match your local path, e.g.:
```python
from pathlib import Path
DATA_PATH = Path("data/sds_datathon_gradsingapore.xlsx")
```

## 4) How to Run (Reproduce Results)
1. Launch Jupyter:
```bash
jupyter notebook
```
(or `jupyter lab`)

2. Open the submission notebook and run **all cells from top to bottom**.
```

## 5) Notes / Assumptions
- Standard-library imports (e.g., `re`, `json`, `math`, `datetime`, `itertools`, `pathlib`) are not listed in `requirements.txt`.
