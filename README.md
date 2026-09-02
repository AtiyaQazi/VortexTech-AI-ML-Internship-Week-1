# VortexTech AI/ML Internship – Week 1

## Data Cleaning and Exploratory Analysis

This project was completed as part of the **VortexTech AI/ML Internship Track – Week 1**.

The objective of this task was to clean a raw dataset using Python and Pandas, perform exploratory data analysis, generate summary statistics, and create basic visualizations.

## Dataset

The **Titanic dataset** was used for this task.

* **Rows:** 891
* **Dataset type:** CSV
* **Main libraries:** Pandas, Matplotlib, Seaborn

## Tasks Completed

The following data preprocessing and exploratory analysis steps were performed:

* Loaded the dataset using Pandas.
* Inspected the dataset using `head()` and `info()`.
* Checked for missing values.
* Checked for duplicate rows.
* Identified the data types of columns.
* Handled missing values:

  * Numerical missing values were handled using the median where appropriate.
  * Categorical missing values were handled using the mode.
  * The `Cabin` column was removed due to a large number of missing values.
* Removed duplicate records.
* Checked and handled data types where required.
* Generated summary statistics including mean, median, descriptive statistics, and value counts.
* Created visualizations using Matplotlib and Seaborn.
* Saved the cleaned dataset as `titanic_cleaned.csv`.

## Visualizations

The notebook includes:

1. Histogram for numerical data distribution.
2. Bar chart for categorical data analysis.

## Files

* `Task1_Data_Cleaning_Analysis.ipynb` – Jupyter Notebook containing the complete analysis.
* `train.csv` – Original Titanic dataset used for analysis.
* `titanic_cleaned.csv` – Cleaned version of the dataset.

## Requirements

Install the required Python libraries using:

```bash
pip install pandas matplotlib seaborn jupyter
```

## How to Run

1. Clone or download this repository.
2. Make sure `train.csv` is in the same folder as the Jupyter Notebook.
3. Install the required libraries.
4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Task1_Data_Cleaning_Analysis.ipynb`.
6. Run the notebook cells from top to bottom.

## Internship Task

**Program:** VortexTech AI/ML Internship Track
**Week:** 1 of 4
**Task:** Data Cleaning and Exploratory Analysis
