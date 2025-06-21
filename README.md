# Task 1: Population Data Visualization  
**Data Science Internship – Prodigy Infotech**

## Objective

This repository presents Task 1 of the Data Science Internship under Prodigy Infotech. The objective was to visualize the distribution of a continuous or categorical variable using a real-world dataset. In this task, population data from the World Bank was analyzed to produce insights on global population distribution.

## Dataset

The dataset was sourced from the [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL), which provides annual population data for countries worldwide. Additional metadata files were used to obtain information such as region and income group classifications.

The following CSV files were used:
- `API_SP.POP.TOTL_DS2_en_csv_v2_81108.csv`: Population data
- `Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_81108.csv`: Country-level metadata

## Methodology

- Loaded and explored the dataset using Python and pandas.
- Reshaped the dataset from wide to long format for time-series analysis.
- Cleaned the data by converting data types and handling missing values.
- Merged the population data with country metadata for richer context.
- Filtered the dataset to extract information for the most recent available year.

## Tools and Technologies

- Python 3.11  
- Libraries: `pandas`, `matplotlib`, `seaborn`  
- Environment: Jupyter Notebook via Visual Studio Code

## Visualizations

### ✅ Completed:
- A **bar chart** showing the **top 10 most populous countries** in the most recent year available.

### 📌 Potential Extensions:
- **Histogram** to display population distribution across all countries
- **Line plot** to illustrate population trends over time
- **Grouped bar charts** to compare populations by region or income group

These visualizations can be implemented using the existing cleaned and merged dataset as part of further exploration.

## Conclusion

This task demonstrates the ability to work with real-world datasets, clean and prepare data for analysis, and create meaningful visualizations. It reinforces foundational skills in data preprocessing, merging, and exploratory data analysis using Python.

## Acknowledgements

This project was completed as part of the Data Science Internship at **Prodigy Infotech**. All data used in this analysis was sourced from the official [World Bank Open Data](https://data.worldbank.org) platform.
