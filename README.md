# Patent Gender Analysis

This repository contains an analysis of patent data from WIPO PATENTSCOPE, focusing on gender distribution among inventors.

## Overview

This project analyzes historical patent data to identify gender patterns among inventors. The analysis includes data from patents spanning multiple decades, utilizing web-scraped data from the World Intellectual Property Organization (WIPO) PATENTSCOPE database. This work is the continuation of the very complete work done by Evelyn McLean, Jane Abdo, Nadia Blostein and Nikola Stikov. Their analysis are described in “Little Science, Big Science, and Beyond,How Amateurs Shape the Scientific Landscape” https://doi.org/10.55458/neurolibre.00031

## Files

- **Analysis_notebook.ipynb**: Main Jupyter notebook containing the complete analysis workflow, data processing, and visualizations
- **inventors_names_gender.csv**: Dataset mapping inventor names to gender classifications
- **popular_names.csv**: Reference dataset of popular names used for gender inference
- **ungendered_names.csv**: List of names that could not be confidently assigned to a gender

## Data Source

The patent data was obtained through web scraping from [WIPO PATENTSCOPE](https://patentscope.wipo.int/search/en/search.jsf).
The gender of the names selected were extracted from: 
USA social security database: https://www.ssa.gov/oact/babynames/decades/century.html
Netherland database: https://www.naamkunde.net/wp-content/uploads/2012/04/top_100_meisjes_jongens_1880-2011.zip
Wikipedia: https://en.wikipedia.org/wiki/List_of_most_popular_given_names
Forebears: https://forebears.io/forenames/most-popular

## Context

This project is for educational and research purposes of the course GBM6330E of Polytechnique Montréal.
