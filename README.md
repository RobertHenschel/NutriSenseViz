# NutriSenseViz - Jupyter Notebooks for CGM Data
This project is about Jupyter Notebooks to create custom visualizations of the glucose data exported from [NutriSense](https://www.nutrisense.io/). If you want to learn more about the notebooks, please have a look at [my blog](https://rhenschel.com/Exploring_NutriSense_Data/), where I talk about every notebook.

# first-chart.ipynb
This notebook takes the exported data from NutriSense as input and produces a [plotly](https://plotly.com/) chart for one day of glucose measurements.

# second-chart.ipynb
This builds on first-chart.ipynb and smooths the curve, adds interpolated values and axis titles.

# chart-with-events.ipynb
Building on second-chart.ipynb, this notebook adds events like meals and exercise to the chart.

# first-analysis.ipynb
Building on second-chart.ipynb, this notebook calculates a few simple glucose statistics for every day and also creates a graph of multiple days of glucose measurements.

# chart-one-day.ipynb
This notebook builds on second-chart.ipynb and first-analysis.ipynb and produces a more advanced chart, that smooths the data, includes exercise and meal "events" that came with the data export from NutriSense and also includes glucose metrics.

# chart-one-day-with-external-data.ipynb
This notebook builds on chart-one-day.ipynb and adds sleep data. The sleep data is not coming from the NutriSense data export but is read from an Excel file that I keep for tracking purposes. The notebook uses [openpyxl](https://openpyxl.readthedocs.io/en/stable/) for reading the Excel file.

# chart-one-day-with-garmin.ipynb
This notebook is very similar to chart-one-day.ipynb in that it charts one day of data, but it replaces "running activities" that came from the NutriSense data export with activities that are imported from Garmin Connect. In order to run this, you will need an account on Garmin Connect, which normally means that you are using a Garmin watch as your fitness tracker.
