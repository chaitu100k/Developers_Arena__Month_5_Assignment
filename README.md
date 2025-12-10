# Developers_Arena__Month_5_Assignment
It includes Developers Arena Internship month 5 assignment files

# Traffic Flow Prediction System (Real-Time Forecasting)

This repository contains a ready-to-submit data science project for **Traffic Flow Prediction**.
It includes Jupyter notebooks for data collection, cleaning, EDA, modeling, evaluation, and a simple dashboard/report.
A sample CSV dataset is included at `data/synthetic_traffic_dataset.csv`. Replace it with your dataset or provide the path
to your CSV in the notebooks where indicated.

## Structure
- `data/` - contains `synthetic_traffic_dataset.csv`
- `notebooks/` - Jupyter notebooks (data_collection.ipynb, cleaning_eda.ipynb, LSTM_feature_engineering.ipynb,  modeling.ipynb, model_evaluation.ipynb, evaluation_dashboard.ipynb)
- `src/` - helper scripts (train.py, preprocess.py, predict.py)
- `report/` - contains a publish-ready PDF and markdown report
- 
## How to use
1. Download the ZIP and extract.
2. Open notebooks in `notebooks/`. Each notebook includes a cell near the top where you can set `DATA_PATH`:
```python
# set your dataset path here (absolute or relative)
DATA_PATH = "data/synthetic_traffic_dataset.csv"
```
3. Run the notebooks in order:
   - `data_collection.ipynb` (examples to load data and optionally download from an online source)
   - `cleaning_eda.ipynb` (cleaning and exploratory plots)
   - `LSTM_feature_engineering.ipynb` (LSTM feature engineering)
   - `modeling.ipynb` (training and testing LSTM/LightGBM model)
   - `evaluation_dashboard.ipynb` (evaluation and results)
4. The `report/` folder contains a PDF report (if generated) and a markdown version you can edit.
