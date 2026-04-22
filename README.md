# Silver Price Analysis

A Python-based exploratory data analysis project for silver price history. The notebook cleans the dataset, inspects the data structure, and produces visualizations that highlight price movement, trading volume, distribution, and relationships between market variables.

## Overview

This repository contains a Jupyter notebook that analyzes historical silver market data stored in `silver_prices_data.csv`. The workflow focuses on preparing the dataset, understanding its statistical properties, and generating charts that support basic market insight.

### What the analysis covers

- Data loading and inspection
- Missing value and duplicate handling
- Date parsing and sorting
- Time-series charts for close, open, high, and low prices
- Trading volume analysis
- Close price distribution
- Correlation matrix visualization
- Derived features such as price change and moving average

## Repository Structure

- `SilverPriceAnalysis.ipynb` - Main analysis notebook
- `silver_prices_data.csv` - Source dataset
- `Graphs/` - Saved visual outputs from the analysis
- `ASSIGNMENT/` - Supporting assignment documents

## Requirements

Install the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

A modern Python 3 environment is recommended.

## How to Run

1. Open the project folder in VS Code or Jupyter Notebook.
2. Ensure `silver_prices_data.csv` is available in the project root.
3. Open `SilverPriceAnalysis.ipynb`.
4. Run the notebook cells from top to bottom.
5. Review the generated charts in the notebook and the `Graphs/` folder.

## Dataset

The dataset includes the following columns:

- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Volume`

The notebook converts the date field to a datetime format, sorts the records chronologically, and uses the market data to build exploratory charts.

## Outputs

The project produces visual analysis such as:

- Closing price over time
- High vs. low prices
- Open vs. close prices
- Trading volume over time
- Close price distribution
- Correlation matrix
- Moving average trend

## Notes

- The notebook is focused on exploratory analysis and visualization rather than prediction modeling.
- If you change the dataset filename or location, update the notebook path accordingly.
- Some charts are also exported into the `Graphs/` folder for reference and presentation use.

## License

No license file is currently included. Add one if you want to define how the project can be used or shared.