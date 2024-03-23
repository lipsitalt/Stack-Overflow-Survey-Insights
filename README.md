<h1 align="center">Stack Overflow Developer Survey Insights 2019:</h1>
<p align="center">
  <br>
  <em>Technology Trends, Demographics, and Implications</em>
  <br>
</p>

![StackOverflow Survey Insights](images/stackoverflow_survey_insights.png)

## Abstract
This repository contains key findings from the analysis of data collected as part of the 2019 Stack Overflow Developer Survey. The survey provides insights into various aspects of technology usage, trends, and demographics among developers.

## Overview
## Objective: 
The primary objective of the annual surveys is to gather data regarding technology usage and trends among developers.
## Dataset: 
I examined a subset of the 2019 dataset (present dataset: N = 11,398; original dataset N ≈ 90,000).
## Audience: 
Developers (current and aspiring), HR professionals, educators, and policy makers.
## Data Source
Link to Stack Overflow’s annual survey data and results
## Data Wrangling
A portion of the dataset (provided by IBM) was loaded and cleaned using SQL and Python’s pandas library.
Cleaning procedure included duplicates removal, data imputation, and data normalization.
Link to dataset provided by IBM
Analysis & Visualization
We conducted exploratory data analysis (EDA) and data visualization using various Python libraries and Cognos. Specifically, we examined the following measures:

Technologies Used in 2019:

Programming languages
Databases
Platforms
Web frameworks
Technologies Desired for the Next Year

Demographics:

Gender
Country
Age
Education level
Key Findings
Compensation & Demographics
Sample size after compensation outlier removal: N = 10,519 (vs. before removal: N = 11,398)
Respondents’ median age: 29
Gender distribution: 93.5% male, 6.5% female
Median compensation: $52,704 USD per year
Positive correlation between compensation and age (r = 0.40)
Median compensation higher for women ($54,956) than men ($52,339)
Programming Language Trends
Findings:

JavaScript and HTML/CSS were the most popular in 2019 and are likely to remain so.
SQL remains popular.
Increasing interest in Python and TypeScript.
Decreasing interest in PowerShell/Bash.
Implications:

Web development remains in high demand.
SQL remains preferred for big data storage and querying.
Python’s popularity reflects AI and ML growth.
Database Trends
Findings:

SQL database programs (especially MySQL) were popular in 2019.
PostgreSQL gaining popularity.
MongoDB popular and gaining interest.
Increasing interest in Elasticsearch.
Implications:

Developers prefer open-source database programs.
NoSQL databases gain popularity for handling nonrelational and unstructured data.
Overall Findings & Implications
Findings:

High usage and interest in JavaScript and HTML/CSS.
Increasing interest in Python.
SQL remains essential.
NoSQL databases gaining interest.
Gender representation gap despite slightly higher compensation for women.
Technology divide between countries.
Implications:

Developers should consider TypeScript alongside JavaScript and HTML/CSS.
Data professionals need SQL and NoSQL competence.
Businesses must adapt to changing technology preferences.
Policy makers should address gender and economic issues.
Interactive Dashboard
Explore the full, interactive Cognos dashboard summarizing technology use, future trends, and demographics of survey respondents here.

Feel free to replace the placeholders with actual links, images, and relevant details specific to your project. Good luck with your Stack Overflow Developer Survey analysis! 🚀👩‍💻👨‍💻
