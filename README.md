# Inflation, Wages and Productivity (UK, ONS) #

## EDA 
+ Line plots,
+ MA (Moving Average) Plots
+ Static Correlation
+ Rolling Correlation (24 months)
+ Seasonal Plots (Business cycle)

## Analysis
### 1. Stationarity Tests
+ Augmented Dickey Fuller (ADF) Test
+ KPSS Test
### 2. Cointegration Tests
+ Johansen Trace Test
### 3. Model Specification
+ Optimal Lag Selection
+ Final VAR specification
### 4. Diagnostics
+ Portmanteau Test
+ Stability Test
+ Normality Test
### 5. Dynamic Analysis
+ Granger Causality Tests
+ Impulse Response Functions (IRF)
+ Forecast Error Variance Decomposition (FEVD)

## Repo Structure
+ 'data/' -> Pre-processed and raw datasets
+ 'data_exploration.ipynb' -> Jupyter notebook of pre-processing and exploratory plots
+ 'model.ipynb' -> Jupyter notebook of diagnostic tests and VAR model

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
