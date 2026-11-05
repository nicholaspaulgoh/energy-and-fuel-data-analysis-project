# Energy and Fuel Data Analysis Project

## Overview

This project explores energy consumption and fuel price data from Spain and France using Python and big data analytics technologies.

It focuses on analysing hourly electricity data from Spain and large-scale petrol station fuel price records from France. Through data processing, exploratory data analysis, statistical techniques and visualisation, the project aims to identify patterns, relationships and potential anomalies within the datasets.

## Objectives

- Explore and understand energy consumption and fuel price datasets.
- Perform data cleaning and preprocessing.
- Apply descriptive and diagnostic analytics.
- Identify trends, patterns and potential anomalies.
- Investigate relationships between variables using correlation analysis.
- Explore distributed data processing using Apache Spark.

## Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| PySpark | Distributed big data processing |
| Jupyter Notebook | Interactive development and analysis |

## Datasets

This project uses three datasets covering electricity consumption and fuel prices.

### 1. French Fuel Price Data (CSV)

- Contains petrol station fuel price records from France.
- Used for data exploration, cleaning and analysis.

### 2. French Fuel Price Data (Parquet)

- Contains fuel price records in Parquet format.
- Used to explore efficient data storage and large-scale processing with PySpark.

### 3. Spanish Electricity Data

- Contains hourly electricity data from Spain.
- Used to investigate electricity consumption patterns and trends.

The original dataset archives are stored in the `data/` directory.

## Areas of Analysis

- **Data Preprocessing:** Cleaning, transforming and preparing datasets for analysis.
- **Descriptive Analytics:** Exploring distributions, summary statistics and trends.
- **Data Visualisation:** Presenting findings through charts and statistical plots.
- **Diagnostic Analytics:** Investigating correlations and potential anomalies.
- **Big Data Processing:** Using PySpark to process and analyse large datasets.

## Project Structure

```text
energy-and-fuel-data-analysis-project/
│
├── data/
│   ├── fuel_in_france_2026_01_to_2026_09_csv.zip
│   ├── fuel_in_france_2026_01_to_2026_09_parquet.zip
│   └── spain_energy_hourly.zip
│
├── notebooks/
│   └── big_data_analytics.ipynb
│
├── visualisations/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/nicholaspaulgoh/energy-and-fuel-data-analysis-project.git
```

### 2. Navigate to the project directory

```bash
cd energy-and-fuel-data-analysis-project
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks/` directory to explore the analysis.

## Project Status

🚧 **In Progress**

This project is currently under development. Further data analysis, visualisations and findings will be added as the project progresses.

## Author

Developed as part of an ongoing Big Data Analytics project.
