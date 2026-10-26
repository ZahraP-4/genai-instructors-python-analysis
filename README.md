# Generative AI Familiarity and Concerns Among University Instructors

## About This Project

In this project, I used Python to analyze survey data about university instructors and their opinions about Generative AI (GenAI).

The dataset includes responses from 178 instructors at William & Mary, a university in the United States.

My main goal was to understand how familiar instructors are with GenAI and what concerns they have about using it in education.

## Data Source

I used a publicly available dataset from a research paper published in 2025:

**Understanding the practices, perceptions, and (dis)trust of generative AI among instructors: A mixed-methods study in the U.S. higher education.**

- [Research Paper](https://doi.org/10.1016/j.caeai.2025.100383)
- [Original Dataset (OSF)](https://osf.io/gve2s/?view_only=ad97f7079ef543d6894f68349ee03ae9)

The original study covered different topics related to GenAI. For my project, I focused on familiarity and concerns among instructors from different academic units.

## Data Ethics and Credits

The original study was approved by the university's Institutional Review Board (IRB), and participants provided informed consent.

The researchers made their anonymized survey data publicly available on OSF.

I used this dataset for my own Python analysis. I cleaned and prepared the data and explored questions related to GenAI familiarity and concerns.

All credit for the original research and dataset belongs to the study's authors.

The MIT license in this repository applies to my own code. The original dataset is subject to its original terms of use.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

## Data Cleaning

Before starting the analysis, I cleaned and prepared the dataset using Python.

I completed these steps:

- Removed unnecessary columns.
- Renamed columns to make them easier to understand.
- Checked missing values and duplicate records.
- Replaced survey codes with readable categories.
- Fixed inconsistent values.
- Prepared the data for analysis.

## Data Analysis

### Analysis 1: GenAI Familiarity by Academic Unit

I wanted to find out how instructors' familiarity with GenAI differs across academic units.

I calculated the percentage of instructors at each familiarity level and created a stacked bar chart to compare the academic units.

**What I found:**

- Business had the highest percentage of instructors with high GenAI familiarity among the identified academic units (95.8%).
- Law also had a high percentage (91.7%).
- Marine Science had the lowest percentage (50.0%).

These results show differences in familiarity among academic units in this survey.

### Analysis 2: GenAI Concerns by Academic Unit

Next, I analyzed the concerns instructors mentioned about GenAI.

Some instructors mentioned more than one concern, so I separated the responses and counted each concern individually.

I also created a heatmap to compare concerns across academic units.

Because the number of instructors was different in each academic unit, I used percentages instead of only comparing the number of responses.

**What I found:**

The most common concerns were:

- Critical Thinking & Learning: 50 mentions
- Academic Integrity: 29 mentions
- AI Literacy & Training: 22 mentions
- Writing & Creativity: 22 mentions
- Accuracy & Misinformation: 22 mentions

Critical Thinking & Learning was the most common concern overall.

It was mentioned by 50% of instructors with categorized concerns in Business and 40.5% in Arts and Sciences.

These percentages are based on instructors who provided valid, categorized concern responses in each academic unit.

## What I Learned

This project helped me practice:

- Cleaning and preparing real survey data.
- Working with missing values and categorical data.
- Using loops and string methods in Python.
- Analyzing data with Pandas.
- Creating charts with Matplotlib and Seaborn.
- Comparing groups using percentages.
- Understanding and explaining data analysis results.

## Power BI Dashboard

I also developed an interactive Power BI dashboard
to explore GenAI adoption, perceptions, and concerns
among university instructors.

The dashboard includes:
- 4 KPI cards
- 5 interactive charts
- Filters for gender, education, academic unit,
  and teaching experience

## Limitations

The dataset only includes instructors from one university. Also, some academic units had a small number of responses, and some concern responses were missing or unclear.

For these reasons, the results may not represent all university instructors in the United States.

## Project Status

This is an ongoing project. So far, I have completed the data cleaning and two exploratory analyses. I plan to add more analysis in the future.
