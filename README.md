# Inflation, Wages and Productivity (UK, ONS) #

## Exploratory analysis
+ Line plots,
+ MA (Moving Average) Plots
+ Static Correlation
+ Rolling Correlation (24 months)
+ Seasonal Plots (Business cycle)

## Analysis
### Stationarity
+ Augmented Dickey Fuller (ADF) Test
+ KPSS test
### Cointegration
+ Johansen Trace Test
### Forecasting
+ VECM Model
+ Pseudo OOS RMSE forecast accuracy

## Repo Structure
+ 'data/' -> Pre-processed and raw datasets
+ 'data_exploration.ipynb' -> Jupyter notebook of pre-processing and exploratory plots
+ 'model.ipynb' -> Jupyter notebook of diagnostic tests and VECM forecasting model

## Reproduce Results
### Step 1) Set up Environment
```bash
python -m venv .venv

# Windows:
.venv\Scripts\activate

# macOS/Linux:
source .venv/bin/activate
```
### Step 2) Install dependencies
```bash
pip install -U pip

pip install -r requirements.txt
```
### Step 3) Run notebooks
```bash
jupyter lab
```
# Open:
data_exploration.ipynb

model.ipynb
