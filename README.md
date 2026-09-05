# Healthcare SQL Analysis

## Overview
SQL-based exploratory analysis of a synthetic healthcare dataset (10,000 patient records), performed using Python, SQLite, and pandas in Google Colab.

## Dataset
- Source: Kaggle "Healthcare Dataset" (synthetic, 15 columns, non-commercial use)
- Fields: patient demographics, medical conditions, admission details, billing, and insurance

## Key Findings
- Six medical conditions (Arthritis, Diabetes, Hypertension, Obesity, Cancer, Asthma) are represented in roughly equal proportion (~9,200-9,300 patients each)
- Obesity and Diabetes carry the highest average billing (~$25,600-$25,800)
- Average length of stay is consistent across all conditions (15.4-15.7 days)
- Adult age groups (18-75) are evenly distributed across conditions; pediatric records are minimal
- Billing amounts are consistent across admission types and insurance providers (~$25,400-$26,000)

## Tools Used
Python, SQLite, pandas, Google Colab

## How to Run
1. Open `healthcare_sql_analysis.ipynb` in Google Colab
2. Upload `healthcare_dataset.csv` when prompted
3. Run all cells top to bottom
