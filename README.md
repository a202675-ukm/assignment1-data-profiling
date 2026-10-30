# Assignment 1: Data Profiling and Quality Remediation

## Team Members

| Name | Matric Number |
|---|---|
| Wei Zhihang | A206275 |

## Purpose

Check and handle data quality problems in the UCI Adult dataset for an educational study of historical census-income records.

The notebook covers missing values, inconsistent formats, numerical validity, repeated profiles, outliers, privacy and bias risks. Handling decisions and remaining limitations are explained.

## Run Instructions

1. Use Python 3.12 and open a terminal in the project folder.
2. Create a virtual environment: `python3 -m venv .venv`
3. Activate it on macOS: `source .venv/bin/activate`
4. Install dependencies: `python -m pip install -r requirements.txt`
5. Start JupyterLab: `python -m jupyterlab`
6. Open `Assignment1_Data_Profiling.ipynb`, restart the kernel and run all cells from top to bottom.

Original files are stored in `data/raw`. Processed files and diagnostic tables are saved in `outputs`.

Internet access is required if the original archive is unavailable. No API key or credentials are required.

## Data Source

Becker, B., & Kohavi, R. (1996). Adult [Data set]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20

Dataset: https://archive.ics.uci.edu/dataset/2/adult

Download: https://archive.ics.uci.edu/static/public/2/adult.zip

Dataset license: Creative Commons Attribution 4.0 International (CC BY 4.0).

Original source files remain unchanged. Processing steps are documented in the notebook.

## Limitations

Missing information, unresolved repeated profiles, extreme values and representation bias remain relevant. Historical US records should not be treated as representative of current Malaysian residents or used for decisions about individuals without further validation.
