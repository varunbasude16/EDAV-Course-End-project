# Electricity Generation and Energy Source Analysis

Course-end project for Exploratory Data Analysis and Visualization (EDAV).
It studies how the world generates electricity, which sources supply it, and
whether it is getting cleaner (2000 to 2025).

## Files

- `electricity_generation_analysis_Remake.ipynb`: full analysis for bigdata (cleaning, Q1 to Q5, charts)
- `electricity_generation_report.docx`: project report
- `data/release_generation_yearly_global.csv`: dataset
  
(data source: (https://ember-energy.org/data/[url](https://ember-energy.org/data/)))

## What I did
- Filled missing values first (fillna, recalculation, capacity estimate)
- Removed summary rows (Total generation, Fossil, etc.) to avoid double counting
- Used NumPy and pandas groupby for statistics, then 5 simple charts

## Key findings
- World generation roughly doubled from 2000 to 2024 (15,325 to 31,071 TWh)
- Fossil share fell from a peak of 68.4% (2007) to 57.7% (2025)
- Solar and wind grew from 0.2% to 17.3% of world generation
- Carbon intensity fell from 528 to 460 gCO2e/kWh
- India still gets about 75% of its electricity from coal

## How to run
1. Put the CSV in the same folder as the notebook
2. Install libraries: `pip install numpy pandas matplotlib seaborn`
3. Open the notebook and run Kernel, then Restart and Run All

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter
