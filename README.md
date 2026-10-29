# Data_Vizualization-Proj-9-
A Python-based sales data analysis project using Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, statistical analysis, and interactive visualizations.
📊 Pandas Analyzer & Data Visualization
Turn raw sales data into meaningful business insights with Python.

A beginner-friendly data analysis project built with Pandas, NumPy,
Matplotlib, and Seaborn. This notebook demonstrates how sales records
can be loaded, cleaned, explored, summarized, and visualized to make
information easier to understand.
✨ Project Overview
The Pandas Analyzer & Data Visualization project is designed to
practice practical data analysis skills using a sample sales dataset. It
uses a Jupyter Notebook divided into small, topic-wise cells so each
step can be run and understood independently.

The included sales_data.csv file contains 120 sample sales
records. Each record includes a sale ID, date, product, region,
quantity, unit price, sales amount, profit, and year. The dataset is for
demonstration and learning purposes, not real business reporting.
🎯 Objectives
- Load sales information from a CSV file.
- Clean data by removing duplicate rows and handling missing values.
- Explore rows, columns, data types, and descriptive summaries.
- Use NumPy arrays for calculations and slicing.
- Search, sort, filter, and split records based on selected criteria.
- Combine DataFrames and summarize sales by region or product.
- Create charts that help explain sales patterns and distributions.
🧰 Tools and Technologies
  Tool               Purpose
  Python             Main programming language
  Jupyter Notebook   Run code in separate cells
  Pandas             Load, clean, transform, and summarize data
  NumPy              Array operations and numerical calculations
  Matplotlib         Create bar, line, scatter, pie, and histogram plots
  Seaborn            Create box plots and a correlation heatmap
  CSV                Store the sample sales dataset
🚀 Features
- Data loading: Reads sales records from sales_data.csv.
- Data cleaning: Removes duplicate rows and fills missing numeric
  or text values.
- Data exploration: Displays the first and last rows, column
  names, data types, and summary statistics.
- Search and filtering: Finds products and filters records by
  region.
- Data transformation: Creates a discounted-sales column and saves
  region-specific records to a separate CSV file.
- DataFrame combinations: Demonstrates concat(), merge(), and
  join().
- Statistical analysis: Calculates total, mean, median, minimum,
  maximum, standard deviation, variance, and percentiles.
- Grouped summaries: Uses groupby() and pivot tables to compare
  sales.
- Visualization: Generates bar charts, line charts, scatter plots,
  pie charts, histograms, box plots, heatmaps, and subplots.
- Chart export: Saves charts to image files such as PNG or JPG.
📁 Project Files
Pandas-Analyzer/
├── Pandas_Analyzer_Full_Working.ipynb
├── sales_data.csv
└── README.md
Keep the notebook and CSV file in the same folder so the notebook can
find the dataset.
⚙️ Getting Started
1. Download or clone the repository
git clone <your-repository-url>
Alternatively, download the repository as a ZIP file and extract it.
2. Install the required libraries
Open a terminal in the project folder and run:
python -m pip install pandas numpy matplotlib seaborn jupyter
3. Open Jupyter Notebook
jupyter notebook
Open Pandas_Analyzer_Full_Working.ipynb in the browser.
4. Run the notebook
Run the cells from top to bottom using Shift + Enter. If prompted,
enter a product name or region. Example product names include Laptop,
Phone, and Tablet; regions include North, South, East, West,
and Central.
📈 What You Can Learn
This project provides practice with importing CSV files, handling
missing values, working with DataFrames and NumPy arrays, applying
statistical functions, grouping records, building pivot tables, and
presenting findings through visualizations. It is also an introduction
to organizing Python analysis work in Jupyter Notebook.
🔮 Possible Improvements
Future versions could include interactive charts, date-range filters, a
graphical dashboard, exportable summary reports, and support for
uploading different sales datasets.
👤 Author
Created as a Python data analysis learning project.
