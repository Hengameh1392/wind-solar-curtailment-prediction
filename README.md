# Wind and Solar Curtailment Prediction 
 
This repository contains code and experiments for forecasting wind and solar curtailment using Temporal Fusion Transformer (TFT) models. 
It builds on previous work with large datasets and data science workflows. 
 
## Setup 
1. Activate environment: `conda activate tft_new` 
2. Install dependencies: `conda install pandas numpy matplotlib pytorch-forecasting pytorch_lightning dask` 
3. Download data from [your cloud storage link, e.g., Google Drive]. Place in `data/` (e.g., wind_data.csv, solar_data.csv). 
4. Run notebooks in `scripts/` using VS Code or Jupyter. 
 
## Experiments 
- Data preprocessing and visualization in `wind_solar_curtailment.ipynb`. 
- TFT model training for curtailment forecasting. 
- Integration with MEF calculations (from previous scripts). 
 
## Outputs 
- Plots in `outputs/plots/`. 
- Predictions in `outputs/predictions/`. 
