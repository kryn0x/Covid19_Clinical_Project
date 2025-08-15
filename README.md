📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on COVID-19 clinical trials data from ClinicalTrials.gov.
The dataset contains details about global COVID-19 related clinical studies, including trial status, phases, locations, demographics, and more.

The goal of this project is to clean, analyze, and visualize the dataset to uncover patterns and trends in the global research effort against COVID-19.

🛠️ Tools & Libraries Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook for analysis and visualization

Dataset: COVID-19 Clinical Trials Dataset

📊 Analysis Performed

Data Cleaning:

Removed irrelevant columns with excessive missing values (Results First Posted, Study Documents).

Filled missing categorical values with "Missing <column_name>".

Filled missing numeric values (Enrollment) with the median.

Extracted Country from Locations column for geographical analysis.

Univariate Analysis:

Top 10 countries with the highest number of trials.

Distribution of trial status, phases, and age groups.

Bivariate Analysis:

Relationship between trial Status and Phases.

Conditions vs Outcome Measures.

Time Series Analysis:

Trend of trials started over time.
