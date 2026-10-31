# Assignment 1: Data Profiling (EDA)

## Group Members
- Nur Nadiah Binti Mohd Rizwan (A216675)
- Aisyah Adriana Binti Ahmad Nazri (A216696)
- Syasya Nabilah Binti Fadzil Azhar (A216839)

## Project Description
This assignment focuses on identifying and handling data quality issues in the Diabetes 130-US Hospitals (1999–2008) dataset. The analysis covers missing values, outliers, duplicate records, invalid values, inconsistent categories, and possible PII and bias risks.

## Dataset Source
Diabetes 130-US Hospitals (1999–2008)

Source: https://www.kaggle.com/datasets/brandao/diabetes

## Tools and Libraries
- Google Colab / Jupyter Notebook
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run the Notebook
1. Download `Assignment1_Diabetes_Data_Profiling.ipynb` and `diabetic_data.csv` from this repository.
2. Open in Google Colab: https://colab.research.google.com/github/A216675-ukm/Assignment-1-Data-Profiling-EDA/blob/main/Assignment1_Diabetes_Data_Profiling.ipynb
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Place `diabetic_data.csv` in the notebook's working directory.
5. Make sure the required Python libraries are installed.
6. Run all cells in order using **Runtime > Run all** in Google Colab.

## Analysis
The notebook includes data sampling, missing value detection and handling, outlier analysis using the IQR method, duplicate checks, categorical validation, diagnostic charts, and an assessment of PII and bias risks.

## Conclusion
The cleaned dataset is more suitable for basic exploratory analysis of hospital readmission patterns. However, some limitations remain, including missing clinical information, possible demographic imbalance, and historical records from 1999 to 2008.
