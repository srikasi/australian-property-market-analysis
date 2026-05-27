# Multimodal Australian Property Market Analysis

Exploratory data analysis, pipeline engineering, and statistical modelling of Australian housing finance trends using RBA interest rate data and ABS statistics.

## Project Overview
This project investigates the structural relationship between RBA cash rate movements and housing finance activity in Australia. It was completed as an independent data engineering and analysis project to apply advanced Python-based data wrangling and statistical modeling workflows to public, multi-source datasets.

*   **Tools and Libraries:** Python, Pandas, NumPy, Scikit-Learn, Jupyter Notebook
*   **Data Architecture Platform:** Open-source unstructured text/CSV data integration
*   **Data Sources:**
    *   Reserve Bank of Australia (RBA) — Cash rate historical data matrix
    *   Australian Bureau of Statistics (ABS) — Housing finance structural statistics

---

## Technical Pipeline & Workflow
*   **Data Ingestion & Curation:** Programmatically loads and inspects disparate RBA and ABS datasets, filtering out non-tabular metadata.
*   **Schema Alignment:** Cleans, standardises, and synchronises inconsistent datetime formats across separate source schemas.
*   **File-System Merging:** Stitches multi-source datasets on aligned date keys into a single, analysis-ready DataFrame (replicating multi-table relational join logic).
*   **Exploratory Data Analysis (EDA):** Evaluates correlations and variances within the combined time-series data arrays.
*   **High-Dimensional Statistical Analysis:** Builds and deploys a Linear Regression model using Scikit-Learn to quantify the exact mathematical relationship between macroscopic interest rate movements and market demand volumes.
*   **Predictive Evaluation:** Generates trend predictions and evaluates statistical model performance outputs.

---

## Core Skills Demonstrated
*   **Data Ingestion & Asset Curation:** Programmatically handling messy, unstructured text and non-tabular formats.
*   **Inter-System Data Standardisation:** Aligning inconsistent data types and formatting variations across disparate sources.
*   **Multivariate Statistical Analysis:** Designing predictive workflows and linear regression models using Scikit-Learn.
*   **Analytical Reporting:** Interpreting complex mathematical trends to deliver clear insights.

---

## Key Finding
Statistical regression modelling indicates a significant inverse relationship between RBA cash rate increases and housing finance volumes — demonstrating a clear structural contraction in housing credit demand parameters as macroscopic interest rates rise.

---

## How to Run
1. Clone this repository: `git clone https://github.com`
2. Install dependencies: `pip install pandas numpy scikit-learn jupyter`
3. Open the workspace: `jupyter notebook banking_data_merge.ipynb`
4. Execute all cells sequentially.

---

## Portfolio Roadmap
This system represents **Project 1** of a 3-project computational portfolio currently under active development.


| Project | Domain / Focus | Status |
| :--- | :--- | :--- |
| **Project 1** | Multimodal Property Market Analysis (Python/Pandas/Regression) | **Complete / In Progress** |
| **Project 2** | Credit Risk Prediction & Classification Workflow (ML) | *Planned* |
| **Project 3** | Regional Water Quality Trend Analysis (QLD Open Data) | *Planned* |

---

**Author:** Dr. Sri Kasi Matta — Technical Data Professional | Brisbane, QLD  
[github.com/srikasi](https://github.com)
