# Penguins Exploratory Data Analysis (EDA)

## Project Overview

This project explores the Penguins dataset using Python, Pandas, Matplotlib, and Seaborn. The purpose is to understand the dataset, clean missing data, identify patterns, and visualize relationships between penguin measurements.

## Dataset

The dataset contains information about penguin species, islands, bill measurements, flipper length, body mass, and sex.

### Columns

- `species`: Penguin species
- `island`: Island where the penguin was recorded
- `bill_length_mm`: Bill length in millimeters
- `bill_depth_mm`: Bill depth in millimeters
- `flipper_length_mm`: Flipper length in millimeters
- `body_mass_g`: Body mass in grams
- `sex`: Penguin sex

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

- Checked dataset dimensions, data types, and summary statistics.
- Identified missing values and duplicate rows.
- Removed two rows containing five missing values each.
- Retained rows with missing values in the `sex` column because their other measurements were useful.
- Checked the unique values of species, islands, and sex.

After removing the two incomplete rows, the dataset contained 342 rows and 7 columns.

## Exploratory Data Analysis

The following analyses were performed:

1. Penguin species distribution across islands
2. Average bill length by sex
3. Relationship between flipper length and body mass
4. Correlation heatmap of numerical variables
5. Distribution of penguin body mass
6. Boxplots of bill depth, bill length, and flipper length
7. Average body mass comparison across species

## Key Findings

- Biscoe Island had the highest number of Gentoo penguins in this dataset.
- Dream Island had more Chinstrap penguins than Adelie penguins.
- All recorded penguins on Torgersen Island belonged to the Adelie species.
- Male penguins had a higher average bill length than female penguins.
- Flipper length and body mass showed a strong positive correlation of approximately 0.87.
- Gentoo penguins had the highest average body mass, at approximately 5076 grams.
- Adelie and Chinstrap penguins had lower average body masses, at approximately 3701 grams and 3733 grams, respectively.

## Visualizations

The project includes visualizations showing:

- Species count by island
- Average bill length by sex
- Flipper length versus body mass
- Correlation heatmap
- Body mass histogram
- Bill depth, bill length, and flipper length boxplots
- Average body mass by species

## Conclusion

This exploratory data analysis identified patterns in penguin species distribution and differences in physical measurements. Gentoo penguins had the highest average body mass, and flipper length was strongly associated with body mass. The visualizations helped summarize the data and compare different groups of penguins.

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Install the required libraries if they are not already installed.
4. Open and run the EDA notebook cells in order.

## Future Improvements

- Explore additional relationships between penguin measurements.
- Compare measurements across species and islands in more detail.
- Build a machine learning model to predict penguin species.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Status:** Completed