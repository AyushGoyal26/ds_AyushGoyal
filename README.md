# ds_AyushGoyal
This project analyzes trading data together with the Fear & Greed Index.
The two CSV files are merged using the date column and basic charts are generated for volume and PnL trends.

# Files in This Project
## 1. notebook_1.ipynb

Main notebook that loads the two CSV files, merges them, performs basic EDA, and generates charts.

## 2. csv_files/

Contains:

fear_greed_index.csv – sentiment data

historical_data.csv – raw trading data

processed_merged.csv – final merged dataset created in notebook_1

## 3. outputs/

Saved charts:

- avg_pnl.png

- volume.png

- pnl_time.png

- volume_time.png

## 4. ds_report.pdf

A simple PDF report with charts and short observations.

## 5. README.md

Basic information about the project.

How to Run

Open notebook_1.ipynb in Colab or Jupyter.

Upload both CSV files :

fear_greed_index.csv

historical_data.csv

Run all cells.

The notebook will merge the data and save charts inside the outputs/ folder automatically.

Output

The notebook produces:

merged dataset (processed_merged.csv)

basic charts for volume and PnL trends

sentiment-wise comparison graphs
