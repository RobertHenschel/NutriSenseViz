# NutriSenseViz
Jupyter Notebooks that create custom visualizations of the data exported from NutriSense.

# first-chart.ipynb
This notebook takes the exported data from NutriSense as input and produces a [plotly](https://plotly.com/) chart for one day of glucose measurements.

# second-chart.ipynb
This builds on first-chart.ipynb and smoothes the curve, adds interpolated values and axis titles.

# first-analysis.ipynb
Building on second-chart.ipynb, this notebook calculates a few simple glucose statistics for every day and then plots the data.

# chart-one-day.ipynb
This notebook builds on first-chart.ipynb and produces a more advanced chart, that smoothes the data and also includes exercise and meal "events" that came with the data export from NutriSense.
