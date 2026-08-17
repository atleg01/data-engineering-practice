# Data Engineering Practice

A collection of beginner data engineering projects built while completing my DataCamp Data Engineering certification. Each notebook focuses on practicing real data handling skills cleaning, transforming, aggregating, and visualizing data using Python and pandas.

## About me
I'm transitioning into data engineering from a finance/HR background (Benefits Specialist) This repo documents my hands on practice as I build toward a junior data engineering role.

## 📁 Projects

### 1. Netflix Movies and TV Shows — Data Exploration
A data cleaning and exploration project using the Netflix Movies and TV Shows dataset.

**What it covers:**
- Inspecting raw data structure, types, and missing values
- Cleaning missing values in `director` and `cast` columns
- Filtering data into Movies vs TV Shows
- Sorting and grouping titles by release year
- Exporting cleaned data (a simple Extract → Transform → Load workflow)

**Tools:** Python, pandas
**Dataset:** [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)


### 2. COVID-19 Global Case Analysis
A time-series analysis project exploring global COVID-19 case data, with a focus on South Africa.

**What it covers:**
- Converting date columns to proper datetime format
- Filtering and analyzing South Africa's case trends
- Comparing confirmed cases across South Africa, Brazil, and India
- Calculating daily new cases from cumulative totals using `.diff()`
- Visualizing case trends with line charts

**Tools:** Python, pandas, matplotlib
**Dataset:** [Novel Corona Virus 2019 Dataset — Kaggle](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

## 🛠 Skills practiced across this repo
Data cleaning · Filtering · Sorting · GroupBy aggregation · Datetime handling · Derived columns · Data visualization · Basic ETL workflow

### 3. Online Retail — Data Cleaning and Revenue Analysis
A data cleaning and business analysis project using a real UK-based 
e-commerce transaction dataset with over 500,000 rows.

**What it covers:**
- Loading and inspecting a large real-world retail dataset
- Removing missing CustomerIDs to retain only trackable transactions
- Filtering out returns and negative quantities for accurate analysis
- Engineering a new `TotalPrice` column (Quantity × UnitPrice)
- Answering real business questions using groupby aggregation:
  - Which country generates the most revenue?
  - What are the top 10 best-selling products?
- Visualising top 10 countries by revenue with a bar chart
- Exporting the cleaned dataset as a new CSV file

**Tools:** Python, pandas, matplotlib
**Dataset:** [Online Retail Dataset — Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

**Key finding:** The UK dominates revenue as expected for a 
UK-based retailer, with PAPER CRAFT, LITTLE BIRDIE emerging 
as the top-selling product by volume.

### 4. Pretoria Weather API Pipeline — JSON & Requests Practice
A data engineering project focused on extracting live weather data 
from a public API using Python, practising core API and JSON handling 
skills.

**What it covers:**
- Encoding and decoding JSON using `json.dumps()` and `json.loads()`
- Calling a live REST API using the `requests` library with proper headers
- Decoding JSON API responses using the `.json()` method
- Sending JSON data using `requests.post()` with the `json=` argument
- Converting live API response data into a pandas DataFrame
- Cleaning and inspecting real-world weather data
- Saving extracted and transformed data to CSV — completing a full 
  Extract, Transform, Load workflow

**Tools:** Python, pandas, requests, json
**Data source:** Open-Meteo Weather API (live Pretoria forecast data)

**Key learning:** This project marks the transition from static 
CSV datasets to live API data extraction — a core data engineering 
skill for building real-world pipelines.
