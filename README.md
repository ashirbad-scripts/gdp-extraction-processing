# GDP Data Extraction and Processing Project

## Overview

This project demonstrates how to extract, process, and store GDP data of countries using web scraping and data processing tools in Python. The data is sourced from an archived Wikipedia page listing countries by nominal GDP.

This project simulates a real-world Data Engineering task where raw data is extracted from the web, cleaned, transformed, and saved for further analysis or business use.

---

## Project Objectives

* Extract GDP data from a webpage using web scraping
* Load and manipulate tabular data using Pandas
* Perform numerical transformations using NumPy
* Convert GDP values from Million USD to Billion USD
* Store the processed data in a CSV file

---

## Data Source

Archived Wikipedia Page:

[https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)](https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29)

The project extracts the table containing GDP values of countries.

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Jupyter Notebook

---

## Project Workflow

### Step 1: Data Extraction

* Use `pandas.read_html()` to extract tables from the webpage
* Select the required table containing GDP data

### Step 2: Data Processing

* Rename and clean columns
* Convert GDP values from Million USD to Billion USD
* Handle missing or invalid values
* Round GDP values to 2 decimal places

### Step 3: Data Storage

* Save the processed data into a CSV file named:

```
Largest_economies.csv
```

---

## Output

The output CSV file contains:

* Country Name
* GDP (Billion USD)

This file can be used for:

* Data analysis
* Visualization
* Reporting
* Further data engineering pipelines


---


## Key Skills Demonstrated

* Web scraping using Pandas
* Data cleaning and transformation
* Numerical processing using NumPy
* Working with real-world datasets
* Exporting structured data

---

## Author

[Ashirbad Routray](https://www.linkedin.com/in/ashirbad-routray-7a872732a/)

Date: 04.02.2026

