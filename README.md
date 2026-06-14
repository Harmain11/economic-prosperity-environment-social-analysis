# Economic Prosperity, Environment & Social Analysis

## Overview
This notebook explores the relationships between economic prosperity (GDP per capita), environmental impact (CO₂ emissions per capita), and social outcomes (life expectancy at birth) across countries. It follows a clean data science pipeline: loading datasets from Our World in Data, cleaning and merging the data, feature engineering GDP income bands, and performing descriptive analyses and visualizations to interpret key trends and correlations.

## Features
- Loads and cleans country-level time series data for CO₂ emissions, GDP per capita, and life expectancy  
- Creates GDP-based income bands for grouping and comparison  
- Generates publication-quality visualizations with confidence intervals and LOWESS trend lines  
- Computes Pearson correlations between key indicators within income groups  
- Saves figures as PNGs for easy inclusion in reports  
- Exports a cleaned merged panel dataset for further analysis  

## Tech Stack
- Python 3  
- Jupyter Notebook / Google Colab compatible  
- pandas, numpy, scipy for data manipulation and statistics  
- matplotlib, seaborn for plotting and visualization  

## How to Use
1. Clone or download the repository.  
2. Open the notebook `economic-prosperity-environment-social-analysis.ipynb` in Jupyter or Google Colab.  
3. Run all cells sequentially to reproduce the analyses and figures.  
4. Review generated figures in the `figs/` directory if running locally.  
5. The cleaned merged dataset is saved as `clean_country_panel.csv` for further use.  

## Status
This notebook is well-organized and formatted for clear presentation and reproducibility on GitHub.