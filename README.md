# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python in Google Colab. The objective is to understand the dataset, identify patterns, detect missing values and outliers, and visualize relationships between different features.

## Dataset

- **Dataset:** Titanic-Dataset.csv
- **Rows:** 891
- **Columns:** 12

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## EDA Steps Performed

- Imported required libraries
- Loaded the dataset
- Explored dataset structure
- Checked data types
- Generated descriptive statistics
- Identified missing values
- Checked duplicate records
- Performed univariate analysis
- Performed bivariate analysis
- Created correlation heatmap
- Detected outliers using boxplots
- Summarized key observations

## Visualizations

The notebook includes:

- Histograms
- Count plots
- Box plots
- Correlation Heatmap
- Pair Plot
- Missing Values Heatmap

## Key Insights

- Most passengers belonged to the 3rd passenger class.
- Female passengers had a significantly higher survival rate than males.
- First-class passengers were more likely to survive.
- The Fare column contains several outliers.
- Missing values are present in the Age, Cabin, and Embarked columns.

## Repository Structure

```
Titanic-EDA/
│── Titanic_EDA.ipynb
│── Titanic-Dataset.csv
│── README.md
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/mohammedabdulr224-alt/Titanic-EDA.git
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Install the required libraries if running locally:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run all notebook cells sequentially.

## Author

**Mohammed Abdul Rahman**
