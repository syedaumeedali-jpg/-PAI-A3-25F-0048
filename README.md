## Running the Notebook

1. Open Assignment3_Programming_for_AI.ipynb in VS Code.
2. Make sure NumPy, Pandas and Matplotlib are installed.
3. Run all notebook cells in order.
4. Check the generated files in the outputs folder.

## Challenges

One challenging part was creating and customizing the visualizations using Matplotlib.
## Project Overview

This assignment covers code tracing, debugging, sensor data analysis, weather and student data cleaning, a dashboard and a 3D surface animation.
Everything is done only with NumPy, Pandas and Matplotlib inside one notebook.
# Sensor Cube (Q3)

Sensor readings of 6 sensors over 10 days were cleaned by replacing the failed -999 values and impossible readings with NaN.
NumPy functions like np.nanmean were then used to find the mean per sensor and the hourly temperature profile.
# Weather Stations (Q4)

The weather data had duplicate rows, mixed date formats, temperatures stored as text like 34.2C and failed values such as -999 for rain and 0 for pressure.
These were cleaned using Pandas, and then a pivot table and heat spell detection were used to compare the five cities.
