# Building-an-ETL-Pipeline

This is a small ETL project I built as part of my data engineering learning.

The goal of the project was to automate the process of extracting, transforming, and loading electricity-related data, which was previously done manually.

### What the project does:

- **Extracts** data from three raw files:
  - A CSV file with electricity sales data
  - A Parquet file 
  - A nested JSON file with electricity capability data
- **Transforms** the sales data:
  - Removes missing values
  - Filters for residential and transportation sectors
  - Creates new columns for month and year
- **Loads** the cleaned data into new CSV or Parquet files

### Tools used:

- Python


This project helped me understand the basics of building ETL pipelines with Python and working with both tabular and nested data.
