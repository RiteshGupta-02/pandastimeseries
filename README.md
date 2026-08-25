# Pandas Time Series Analysis

This project explores time-series data analysis using Python and pandas. The notebook in this repository loads a monthly dataset, formats it as a time index, performs resampling, calculates differences, and visualizes trends with rolling averages.

## Project files

- `timeSeries.ipynb` — Jupyter notebook containing the analysis workflow
- `LTOTALNSA.csv` — source dataset used for the time-series exploration

## What the notebook covers

- Importing and reading CSV data
- Setting the date column as the DataFrame index
- Creating a date range and aligning the time index
- Resampling data by month and quarter
- Plotting the original series and aggregated views
- Calculating first differences to analyze change over time
- Applying a rolling mean to smooth the series
- Visualizing trends and fluctuations with matplotlib

## Dataset

The project uses the `LTOTALNSA` dataset, which appears to contain a monthly time series. The notebook reads the dataset, indexes it by `observation_date`, and transforms it into a pandas time series for analysis.

## Requirements

Install the necessary Python packages before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn
```

## Run the notebook

Open `timeSeries.ipynb` in Jupyter Notebook or VS Code and run the cells in order.

## Related roadmap

This project follows the concepts covered in the Pandas Time Series roadmap:

https://roadmap.sh/projects/pandas-time-series
