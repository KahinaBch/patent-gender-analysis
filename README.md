# Patent Gender Analysis

This repository contains an analysis of patent data from WIPO PATENTSCOPE, focusing on gender distribution among inventors.

## Overview

This project analyzes historical patent data to identify gender patterns among inventors. The analysis includes data from patents spanning multiple decades, utilizing web-scraped data from the World Intellectual Property Organization (WIPO) PATENTSCOPE database.

## Files

- **Analysis_notebook.ipynb**: Main Jupyter notebook containing the complete analysis workflow, data processing, and visualizations
- **inventors_names_gender.csv**: Dataset mapping inventor names to gender classifications
- **popular_names.csv**: Reference dataset of popular names used for gender inference
- **ungendered_names.csv**: List of names that could not be confidently assigned to a gender

## Data Source

The patent data was obtained through web scraping from [WIPO PATENTSCOPE](https://patentscope.wipo.int/search/en/search.jsf).

### Data Collection Method:
1. In the main page, set "Field" to **Publication Date**
2. Enter the year of interest in "Search terms..."
3. Set "Sort" to **Relevance** and "Per page" to **200**

## Requirements

The analysis uses the following Python libraries:
- pandas
- plotly
- country_converter
- Additional dependencies as specified in the notebook

## Usage

Open `Analysis_notebook.ipynb` in Jupyter Notebook or JupyterLab to explore the analysis.

## License

This project is for educational and research purposes.
