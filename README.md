# Patient Readmission Prediction

Analysis and modeling of 30-day hospital readmission using the Diabetes 130-US Hospitals dataset. The notebook includes data preparation, patient-grouped train/test splitting, feature engineering, XGBoost evaluation, risk ranking, and SHAP analysis.

## Project files

- `notebooks/patient_readmission_analysis.ipynb`: analysis and modeling notebook
- `data/diabetic_data.csv`: encounter-level data
- `data/IDS_mapping.csv`: ID descriptions
- `requirements.txt`: Python dependencies

## Run

From this directory, install dependencies and open the notebook:

```bash
python -m pip install -r requirements.txt
jupyter notebook notebooks/patient_readmission_analysis.ipynb
```

The model is for analysis and educational use only; it is not a clinical decision system.