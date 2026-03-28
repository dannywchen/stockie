# Stockie Notebook Setup

This project contains a hackathon notebook at `finance.ipynb`.

## First-time setup

Create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Launch Jupyter

```bash
source .venv/bin/activate
jupyter lab
```

Then open `finance.ipynb`.

## Dataset

Download and extract the Kaggle dataset so the folder contains:

- `Stocks/`
- `ETFs/`

The notebook will auto-detect these common locations:

- `./archive`
- `./price-volume-data-for-all-us-stocks-etfs`
- `~/Downloads/archive`
- `~/Downloads/price-volume-data-for-all-us-stocks-etfs`

If auto-detect fails, set `DATASET_ROOT` in the notebook to the extracted dataset folder.

## Recommended path

The easiest option is to unzip the Kaggle dataset into this repo as:

```text
stockie/archive/Stocks
stockie/archive/ETFs
```
