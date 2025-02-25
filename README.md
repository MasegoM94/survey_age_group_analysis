# Survey Data Analysis with Statistical Tests

## Overview
This repository provides a Python-based solution for analyzing survey data using various statistical tests and visualisations. The main focus is on applying the **Kruskal-Wallis** and **Chi-Square tests** to understand relationships between categorical and ordinal data in survey responses.

The dataset used for this example is synthetically generated, mimicking a survey about community engagement and event preferences across different age groups.

## Key Features
- **Kruskal-Wallis Test**: Used to assess whether there are significant differences in the community engagement scores across different age groups.
- **Chi-Square Test for Independence**: Applied to examine relationships between categorical variables such as **Preferred Event Type** and **Age Group**.
- **Visualisation**: Includes various plots (count plots, box plots, heatmaps) to visually explore the survey data.

## Requirements
To run this analysis, the following Python packages are required:
- `pandas`
- `numpy`
- `scipy`
- `seaborn`
- `matplotlib`

You can install them via pip:
```bash
pip install pandas numpy scipy seaborn matplotlib
```

## Usage

Run the script to generate synthetic survey data.  
The script will:

- Visualise the distribution of age groups, community engagement scores, preferred event types, and volunteering participation.
- Perform statistical tests such as the Kruskal-Wallis test and Chi-Square test to analyse relationships between variables.
- Generate additional insights using post-hoc analysis and adjusted residuals.

The script will also generate several plots:

- Distribution charts (count plots)
- Boxplots for community engagement by age group
- Stacked bar chart and heatmaps for preferred event types by age group

## Statistical Tests Applied

- **Kruskal-Wallis Test**: Used to determine if there are significant differences in community engagement scores between different age groups.
- **Chi-Square Test**: Used to evaluate the relationship between age group and preferred event type, and between age group and volunteering participation.

## License

This project is open-source and available for non-commercial use.
