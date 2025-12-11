# CIS9650-Term-Project
# 📊 Analysis of Healthcare Accessibility & Physician Quality in New York State

## Overview
This project analyzes primary care physician data across New York State in order to understand provider quality rating, patient satisfaction, and geographic trends in healthcare access. After the team has cleaned the dataset, we performed descriptive and visual analysis across specialties, ratings, review volumes, and ZIP codes. Our findings show that most physicians maintain high ratings, and convenient location across specialties. As healthcare consumers increasingly rely on online reviews to choose providers, understanding patterns in physician ratings, geographic trends, and specialty performance has practical value for both patients and healthcare administrators.

## Research Questions
We focused on three key analytical questions:
1. How do physician ratings vary across specialties and geographic regions?
2. What is the relationship between the amount of reviews and physician rating?
3. Which cities or ZIP codes show the highest concentration of highly rated physicians?
By cleaning the data and generating descriptive statistics, we visualized rating distributions, specialty patterns, and geographic trends across the state. These insights can help patients make more informed decisions and support medical organizations in targeting locations where services or accessibility can be improved.

## Tools & Technology
This project was completed using the following tools:
* Python (Jupyter Notebook)
* Pandas - data cleaning, grouping, and feature engineering
* NumPy - numerical operations
* Matplotlib - data visualization
* Seaborn - enhanced statistical plots
* gcsfs - access to Google Cloud Storage data

## Data Preparation
Key data preparation steps include:
* Removing missing, duplicated, or NULL records
* Standardizing specialty and location fields
* Creating indicator columns (e.g., offers_telehealth)
* Generating email fields for analysis
* Filtering for primary car physicians across NYS
* Aggregating data at the ZIP code and city level

In addition, we examined the availability of services through remote video visits by analyzing the availability of telehealth services based on ZIP code location. We created additional columns, such as indicators of whether a provider offers telehealth services and a generated email address for contacting them, to provide us with a clearer view of our data and assist in recognizing trends and areas where additional support is needed in providing access to healthcare services.

## Deliverables 
This repository includes:
* Jupyter Notebook with full analysis
* Visualizations summarizing key trends
* Executive summary integrated within the notebook
