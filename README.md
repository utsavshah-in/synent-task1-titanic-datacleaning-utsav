# Task 1: Titanic Dataset - Data Cleaning

## Objective
Clean and preprocess the Titanic dataset to make it ready for analysis — handle missing values, remove duplicates, fix data types, and improve column readability.

## Steps Performed
1. Loaded the dataset and did an initial inspection (shape, info, describe).
2. Checked missing values and visualized them using a heatmap.
3. Handled missing values:
   - `Age` → filled with median
   - `Embarked` → filled with mode
   - `Cabin` → dropped (if present, too many missing values)
4. Checked and removed duplicate rows.
5. Fixed data types — converted `Survived` and `Pclass` to categorical.
6. Renamed columns for better readability (e.g., `SibSp` → `Siblings_Spouses`).
7. Saved the cleaned dataset as `titanic_cleaned.csv`.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for missing value heatmap)
- Jupyter Notebook

## Outcome
A fully cleaned Titanic dataset with no missing/duplicate values, correct data types, and readable column names — ready for further EDA or modeling.

## Files
- `task1_cleaning.ipynb` — notebook with all steps
- `titanic.csv` — raw dataset
- `titanic_cleaned.csv` — cleaned dataset
- `missing_values_heatmap.png` — visualization of missing data

## Demo Video
[Watch the demo](https://drive.google.com/file/d/1IxJWIsMP-e0xyPLWGZ_FqQN4eg1S_pl8/view?usp=drive_link)
