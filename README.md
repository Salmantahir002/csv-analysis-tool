📊 CSV Statistical Analyzer
Description:
A web-based tool that allows users to analyze CSV files interactively. It provides statistical summaries, data visualizations, missing value handling, duplicate management, and more — all within a simple, user-friendly interface.
Features:
Upload and preview CSV files

Upload any CSV dataset

Instantly preview the data in a table format

View dataset structure and column details

Handle missing values

Detect missing values automatically

Options to fill, drop, or ignore missing records

See results instantly after processing

Manage duplicate records

Identify and remove duplicate rows

Option to preview duplicates before deleting

Descriptive statistics

View mean, median, mode, min, max, and standard deviation for numeric columns

Summary displayed for each feature

Top features viewer

Display top 5 or top N features based on user selection

Compare data values visually

Data visualization

Generate comparative analysis plots between different columns

Visualize data using histograms, scatter plots, and bar charts

Code generator button

A button that shows the Python code behind each analysis

Copy and reuse the code directly in Jupyter Notebook

How it works:

Upload a CSV file from your computer.

The app loads the data and shows key statistics.

Choose actions like handling missing values, dropping duplicates, viewing top features, or performing comparative analysis.

Generate Python code snippets for the selected actions.

Technologies used:
Frontend: HTML, CSS, JavaScript
Backend: Python (Flask or Streamlit depending on implementation)
Libraries: Pandas, NumPy, Matplotlib, Seaborn (optional for plots)

Folder structure:
app.py – main application file
templates/ – contains HTML files
static/ – contains CSS, JS, and assets
sample_data/ – sample CSV files (optional)
README.md – documentation

Future improvements:

Add correlation matrix visualization

Allow exporting of processed CSV files

Include a machine learning preview (feature importance or predictions)

Add a dark or light theme switch

Use cases:
This project is suitable for:

Data analysts who need quick insights from datasets

Students learning Python data analysis

Developers who want a lightweight analysis dashboard

Author:
Salman Tahir
Computer Science Student and Data Analyst

License:
This project is licensed under the MIT License. You can use, modify, and share it freely.
