# Code for Data Mining Proj1 Paper "When Is a Household Load Forecast Worth Acting On? Decision-Aligned Forecasting for EDF Tempo Red Day"

## Environment setup

install Python 3.13 and create a virtual environment for Jupyter notebooks:
```bash
python3.13 -m venv .venv-notebooks
source .venv-notebooks/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

download [dataset](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption) and put it in `data/` folder. The dataset is from UCI Machine Learning Repository, and the original dataset is in French Sceaux, 2006–2010.

## Reproducing Figures and Tables
To reproduce the paper figures and tables, simply run the Jupyter notebook `Paper_ordered_experiments.ipynb` in order. `Final_experiments.ipynb` contains more detailed experiments and analysis.