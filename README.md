# Programming for AI - Assignment 3

How to run: open `Assignment3_Programming_for_AI.ipynb` in Jupyter Notebook, keep the `data/` folder next to it, and choose Kernel > Restart and Run All. Only numpy, pandas and matplotlib are used. The notebook creates the `outputs/` folder with `dashboard.png`, `dashboard.pdf` and `wave.gif`.

One thing that was hard: the weather file had two date formats mixed together. A normal month-first parse of the DD/MM/YYYY dates fails or gives the wrong month, so I parsed each format separately and checked the date range.
