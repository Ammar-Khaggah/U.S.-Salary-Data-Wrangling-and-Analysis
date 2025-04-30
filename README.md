# U.S.-Salary-Data-Wrangling-and-Analysis

# U.S. Salary Data Wrangling

A data engineering project focused on cleaning, transforming, and optimizing a large-scale U.S. salary dataset (140K+ records) for downstream machine learning tasks. The project simulates a real-world ETL pipeline using pandas and NumPy for advanced data preprocessing and preparation.

---

## 🔍 Overview

- Processed over 140K salary records using pandas for high-volume data wrangling.
- Handled missing values, removed duplicates, and normalized categorical variables.
- Applied label encoding and numerical transformations to prepare features for ML.
- Conducted visual analysis using Seaborn and Matplotlib before and after cleaning.
- Designed a modular pipeline reflecting real-world ETL and data cleaning workflows.

---

## 📊 Technologies Used

- Python, Jupyter Notebooks  
- pandas, NumPy  
- Seaborn, Matplotlib  
- LabelEncoder, DataFrame transformations  

---

## 🧱 Project Structure

Salary-Data-Wrangling/
│
├── data/                      # Raw and cleaned salary dataset (CSV format)
│
├── notebooks/                 # Modular notebooks for each step
│   ├── 01_data_loading.ipynb
│   ├── 02_data_inspection.ipynb
│   ├── 03_data_cleaning.ipynb
│   ├── 04_duplicate_removal.ipynb
│   ├── 05_missing_value_treatment.ipynb
│   ├── 06_encoding_transformation.ipynb
│   ├── 07_visualization_before_cleaning.ipynb
│   ├── 08_visualization_after_cleaning.ipynb
│   └── 09_export_clean_data.ipynb
│
├── visuals/                   # Heatmaps, histograms, and bar plots
│
├── requirements.txt           # Python dependencies
│
└── README.md                  # Project documentation
