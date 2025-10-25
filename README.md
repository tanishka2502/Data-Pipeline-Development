# Data-Pipeline-Development
A Python ETL pipeline that automates data preprocessing and transformation. It loads raw CSV data, cleans and encodes features using pandas and scikit-learn, and saves the processed data for analysis or modeling. Simple, automated, and reproducible.
# ETL Pipeline Project

## Description
This project automates an ETL pipeline:
1. Extract data from CSV files
2. Transform data (handle missing values, encode categorical variables, scale numerical features)
3. Load cleaned data to new CSV files

## Folder Structure
- `data/raw/` : Raw input CSV files
- `data/processed/` : Cleaned and transformed CSV files
- `scripts/etl_pipeline.py` : Python script version
- `notebooks/ETL_pipeline.ipynb` : Notebook version with explanations

## How to Run
1. Place your raw CSV files in `data/raw/`
2. Run the script:
```bash
python scripts/etl_pipeline.py
Check data/processed/ for cleaned CSV
