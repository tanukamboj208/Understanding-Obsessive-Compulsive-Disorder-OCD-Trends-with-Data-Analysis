# Understanding-Obsessive-Compulsive-Disorder-OCD-Trends-with-Data-Analysis
This project performs exploratory data analysis (EDA) on an anonymized OCD (Obsessive-Compulsive Disorder) patient dataset using Python. The analysis focuses on trends in diagnosis dates, ethnicity distribution, and Y-BOCS severity scores.
<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDORZ-dFxEm6zVYZ89i_HvjiD5zS5xHugCvA&s" alt="Project Logo" width="300">
</p>

## Project summary
This project cleans and analyzes a clinical dataset of patients diagnosed with Obsessive-Compulsive Disorder (OCD). Key goals:
- Fix Excel date storage issues and extract diagnosis month/year
- Compute patient counts by month/year
- Visualize ethnicity distribution (pie chart)
- Compare Y-BOCS scores (Obsessions & Compulsions) by gender
- Provide cleaned dataset and charts for reporting

  ## Dataset Overview

The dataset contains 1500 patient records and includes:

- Gender
- Ethnicity
- OCD Diagnosis Date
- Y-BOCS Score (Obsessions)
- Y-BOCS Score (Compulsions)
- Treatment-related fields

Note: Dataset is used only for academic and analysis purposes.
## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Excel (initial review)

 ## Data Cleaning Steps

Handled missing values

Fixed incorrectly interpreted Excel date column

Extracted new features:
- Diagnosis_Year
- Diagnosis_Month

## Analysis Performed

- Count of patients by year and month
- Ethnicity distribution
- Comparison of obsession and compulsion scores by gender
- Trend insights from diagnosis timeline

## Visualizations

The notebook includes:

- Pie chart: Ethnicity distribution
- Bar chart: Patients diagnosed per year
- Line charts: Y-BOCS score comparison by gender
All charts created using Matplotlib only.

## Key Findings (Summary)

- Diagnosis frequency increased significantly in later years.
- Ethnicity distribution shows dominance of certain groups.
- Male and female total Y-BOCS scores are close, indicating similar severity patterns.
