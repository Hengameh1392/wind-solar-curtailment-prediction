# Wind and Solar Curtailment Prediction 
 
Forecasting wind and solar curtailment using Temporal Fusion Transformer (TFT) models, with MEF calculations and wavelet preprocessing for emissions and grid analysis. 
 
## Setup 
1. Activate environment: `conda activate tft_new` 
2. Install dependencies: `conda install pandas numpy matplotlib pytorch-forecasting pytorch_lightning statsmodels pywt dask` 
3. Download data from [your cloud storage link, e.g., Google Drive]. Place in `data/` (e.g., wind_data.csv, solar_data.csv). 
4. Run notebooks in `scripts/` using VS Code or Jupyter. 
 
## Structure 
- `scripts/`: Notebooks and scripts (e.g., `wind_solar_curtailment.ipynb`). 
- `data/`: Datasets (e.g., `wind_data.csv`, `solar_data.csv`). 
- `outputs/plots/`: Visualizations (e.g., time series plots). 
- `outputs/predictions/`: Forecast results (e.g., CSV files). 
 
## Experiments 
- Data preprocessing with wavelet transforms (based on prior work, Rý: 0.86 solar, 0.81 wind). 
- TFT models for curtailment forecasting. 
- MEF calculations for emissions impact (from `mef_ols_regression_one_week.py`). 
