# Australian Property Market Analysis

Exploratory data analysis and predictive modelling of Australian housing finance trends using RBA interest rate data and ABS housing finance statistics.

## Project Overview

This project investigates the relationship between RBA cash rate movements and housing finance activity in Australia. It was completed as a self-directed data analysis project to develop practical Python data and machine learning skills.

**Tools and Libraries:** Python, Pandas, NumPy, Scikit-Learn, Jupyter Notebook

**Data Sources:**
- Reserve Bank of Australia (RBA) — cash rate historical data (public dataset)
- Australian Bureau of Statistics (ABS) — housing finance statistics (public dataset)

## What This Notebook Does

- Loads and inspects RBA and ABS datasets from CSV files
- Cleans and standardises inconsistent date formats across both datasets
- Merges the two datasets into a single analysis-ready dataframe
- Explores relationships between interest rate changes and housing credit volumes
- Performs exploratory data analysis (EDA) on combined time-series data
- Builds a Linear Regression model to quantify the relationship between RBA cash rate movements and housing finance volumes
- Generates predictions and evaluates model output

## Key Skills Demonstrated

- Data ingestion and cleaning with Pandas
- Handling real-world messy data (inconsistent formats, non-tabular metadata)
- Merging multi-source datasets on date keys
- Time-series data preparation and exploratory analysis
- Linear Regression modelling using Scikit-Learn
- Interpreting and communicating model results

## Key Finding

Linear regression modelling indicates a significant inverse relationship between RBA cash rate increases and housing finance volumes — as interest rates rise, housing credit demand contracts measurably.

## How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas numpy scikit-learn jupyter`
3. Open `banking_data_merge.ipynb` in Jupyter Notebook
4. Run all cells in order

## Status

Work in progress — this is Project 1 of a 3-project data portfolio currently under development.

| Project | Topic | Status |
|---|---|---|
| Project 1 | Australian Property Market Analysis | In progress |
| Project 2 | Credit Risk Prediction (ML) | Planned |
| Project 3 | Water Quality Trend Analysis (QLD) | Planned |

## Author

Sri Kasiviswanathan — Data Analyst | Brisbane, QLD  
github.com/srikasi
