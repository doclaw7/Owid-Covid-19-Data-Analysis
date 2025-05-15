<<<<<<< HEAD
# Owid-Covid-19-Data-Analysis
=======
# OWID COVID-19 Data Analysis

This Jupyter Notebook provides an exploratory data analysis of the COVID-19 pandemic using the [Our World in Data (OWID)](https://ourworldindata.org/covid-cases) dataset. The analysis focuses on comparing the pandemic's impact and response in Kenya, India, and the United States, with additional global insights.

## Features

- **Data Cleaning & Exploration:**  
  Loads the OWID COVID-19 dataset, checks for missing values, and previews the data.

- **Country-Specific Analysis:**  
  Filters and displays COVID-19 data for Kenya, India, Japan, and China.

- **Comparative Visualizations:**  
  - Plots total and daily new COVID-19 cases for Kenya, India, and the USA.
  - Visualizes total deaths and calculates death rates.
  - Shows cumulative vaccinations and the percentage of vaccinated populations.
  - Bar charts for total cases by country.
  - Pie charts for vaccinated vs. unvaccinated populations.

- **Global Choropleth Map:**  
  Uses Plotly to display a world map of total COVID-19 cases by country.

- **Key Insights & Recommendations:**  
  Summarizes findings, highlights anomalies, and suggests actions for improved data collection and pandemic response.

## Requirements

- Python 3.7+
- Jupyter Notebook or VS Code with Jupyter extension
- Libraries: `pandas`, `matplotlib`, `plotly`, `IPython.display`

Install dependencies with:
```bash
pip install pandas matplotlib plotly
```

## Usage

1. Download the latest `owid-covid-data.csv` from [OWID](https://github.com/owid/covid-19-data/tree/master/public/data).
2. Place the CSV file in the same directory as the notebook.
3. Open the notebook in Jupyter or VS Code and run all cells.

## Exporting Results

- To export the notebook as PDF, install a TeX distribution (e.g., MiKTeX) or export as HTML and print to PDF from your browser.

---

**Author:**  
Dr. Osiro Lawrence  
*For educational and analytical purposes only.*
>>>>>>> d09794f (initial commit)
