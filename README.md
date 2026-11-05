
# CodeAlpha Task 2: Unemployment Analysis with Python

## 1. Project Overview

This project was completed as part of the **CodeAlpha Data Science Internship – Task 2: Unemployment Analysis with Python**.

The objective of this project is to analyze unemployment rate data in India using Python, perform data cleaning and exploratory data analysis (EDA), visualize unemployment trends, and investigate the impact of the COVID-19 pandemic on unemployment rates.

The project explores regional differences, rural and urban unemployment patterns, labour force participation, and relationships between employment indicators.

## 2. Project Objectives

The main objectives are:

- Analyze unemployment rate data using Python.
- Clean and preprocess the datasets.
- Explore unemployment trends over time.
- Investigate changes in unemployment during the COVID-19 period.
- Identify regions with the highest and lowest unemployment rates.
- Compare unemployment rates in rural and urban areas.
- Examine labour force participation across regions.
- Identify relationships between unemployment and other employment indicators.
- Present meaningful insights through data visualizations.

## 3. Datasets

Two datasets were used for this analysis.

### Dataset 1: Unemployment in India

**File:** `Unemployment in India.csv`

- Covers May 2019 to June 2020.
- Contains regional unemployment information.
- Includes rural and urban observations.
- Provides estimated unemployment rates, employment figures, and labour participation rates.

### Dataset 2: Unemployment Rate up to November 2020

**File:** `Unemployment_Rate_upto_11_2020.csv`

- Contains observations from January 2020 to October 2020.
- Includes regional unemployment and labour participation information.
- Provides geographical coordinates for regions.

**Note:** The two datasets have overlapping periods. They were analyzed separately to avoid double-counting observations.

## 4. Technologies and Libraries

The project was developed using:

- Python
- Jupyter Notebook
- Pandas – Data manipulation and cleaning
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization

## 5. Project Methodology

The project followed these steps:

### Step 1: Data Collection
Loaded the two unemployment datasets into Python using Pandas.

### Step 2: Data Cleaning
- Removed completely empty rows.
- Removed duplicate records.
- Standardized column names.
- Converted date columns into datetime format.
- Standardized frequency labels.
- Checked missing values and data consistency.

### Step 3: Exploratory Data Analysis (EDA)
- Examined dataset dimensions and data types.
- Calculated descriptive statistics.
- Analyzed unemployment rates across regions.
- Explored labour participation rates.
- Compared rural and urban unemployment.

### Step 4: Data Visualization
Created charts to identify patterns and communicate findings.

### Step 5: COVID-19 Impact Analysis
Compared unemployment rates before and during the selected COVID-19 period.

For this analysis:
- Before COVID-19: May 2019 – February 2020.
- During COVID-19: March 2020 – June 2020.

## 6. Key Findings and Insights

The analysis revealed the following findings:

### Monthly Unemployment Trends
- Unemployment rates were relatively stable during much of 2019 and early 2020.
- A sharp increase occurred during April and May 2020.
- The unemployment rate declined in the following months.

### Regional Analysis
- Haryana recorded the highest average unemployment rate in Dataset 2.
- Meghalaya recorded the lowest average unemployment rate in Dataset 2.

### COVID-19 Impact
- The average unemployment rate increased from approximately 9.51% before COVID-19 to 17.77% during the selected COVID-19 period in Dataset 1.
- This represents an increase of approximately 86.91% relative to the earlier average.

### Rural vs Urban Analysis
- Urban areas had a higher average unemployment rate (13.17%) than rural areas (10.32%).
- Rural unemployment experienced a larger relative increase during the selected COVID-19 period.

### Labour Participation and Correlation
- Meghalaya recorded the highest average labour participation rate.
- The regional comparison showed a very weak negative correlation (-0.106) between average unemployment and average labour participation.

**Important:** These findings describe patterns in the available datasets. They do not establish that COVID-19 alone caused the observed changes.

## 7. Project Visualizations

The following visualizations were created and saved in the `visualizations/` directory.

1. Monthly unemployment trend (2019–2020).
2. Monthly unemployment trend (2020).
3. Top 10 regions with the highest unemployment rates.
4. Bottom 10 regions with the lowest unemployment rates.
5. Average labour participation rate by region.
6. Unemployment vs labour participation by region.
7. Unemployment before and during COVID-19.
8. Rural vs urban unemployment comparison.
9. Rural vs urban unemployment before and during COVID-19.
10. Correlation heatmap.

## 8. Project Structure

```text
CodeAlpha_UnemploymentAnalysis/
│
├── data/
│   ├── Unemployment in India.csv
│   └── Unemployment_Rate_upto_11_2020.csv
│
├── notebooks/
│   └── unemployment_analysis.ipynb
│
├── visualizations/
│   ├── monthly_unemployment_trend.png
│   ├── monthly_unemployment_trend_2020.png
│   ├── regional_unemployment_top10.png
│   ├── regional_unemployment_bottom10.png
│   ├── labour_participation.png
│   ├── unemployment_vs_participation.png
│   ├── covid_impact.png
│   ├── rural_urban_comparison.png
│   ├── rural_urban_covid_comparison.png
│   └── correlation_heatmap.png
│
├── requirements.txt
└── README.md
```

## 9. How to Run the Project

### Prerequisites
- Python 3.10 or later
- Jupyter Notebook

### Installation

Clone the repository:

```bash
git clone https://github.com/Fevenes/CodeAlpha_UnemploymentAnalysis.git
```

Navigate to the project directory:

```bash
cd CodeAlpha_UnemploymentAnalysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

`notebooks/unemployment_analysis.ipynb`

Run the notebook cells to reproduce the analysis.

## 10. Conclusion

This project demonstrates how Python and data analysis libraries can be used to investigate unemployment patterns and extract meaningful insights from real-world datasets.

The analysis identified significant changes in unemployment rates during 2020, regional differences, rural and urban disparities, and relationships between labour market indicators.

Through data cleaning, exploratory data analysis, statistical comparison, and visualization, this project provided practical experience in applying data science techniques to an economic and social issue.

## 11. Internship Information

**Organization:** CodeAlpha  
**Domain:** Data Science  
**Task:** Task 2 – Unemployment Analysis with Python

**Author:** Feven Esayas  
**GitHub:** [@Fevenes](https://github.com/Fevenes)
