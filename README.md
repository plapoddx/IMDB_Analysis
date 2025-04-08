# Academic Project: Analyzing IMDB Datasets with PySpark and AWS EMR

## Overview
This academic project demonstrates the use of big data tools and infrastructure to analyze IMDB datasets using PySpark on an AWS EMR cluster. The project focuses on building a scalable data pipeline, conducting genre and job role analyses, and answering structured and exploratory questions about the IMDB dataset.

## Technologies Used
- **PySpark**
- **AWS EMR**
- **Jupyter Notebook**
- **S3 (Amazon Simple Storage Service)**
- **Pandas & Matplotlib**

## Project Objectives
- Provision a Spark cluster using AWS EMR.
- Connect to the cluster through Jupyter Notebook.
- Read large IMDB datasets from a public S3 bucket.
- Perform data transformations and actions using PySpark.
- Generate insights from movie genres, job roles, and individual actors.
- Visualize results using bar charts.



## Key Tasks

### Part I: Installation and Initial Setup
- Imported necessary libraries (pandas, matplotlib).
- Loaded IMDB datasets into Spark DataFrames directly from an S3 bucket.
- Displayed dataset overviews (rows and columns).

### Part II: Analyzing Movie Genres
- Denormalized genre strings for analysis.
- Counted total unique genres.
- Calculated average ratings per genre.
- Visualized top genres using a horizontal bar chart.

### Part III: Analyzing Job Categories
- Identified and counted unique job categories.
- Listed top job categories.
- Created a bar chart to represent top job categories.

### Part IV: Answering Exploratory Queries
- Filtered and listed movies released in 2003 with over 50,000 votes and a rating above 8.
- Analyzed Cillian Murphy’s filmography since 2007.
- Counted Zendaya’s film appearances by year.
- Calculated Audrey Hepburn’s age at the time of death.
- Found Chris Evans' highest-rated movie.
- Identified movies co-starring Johnny Depp and Helena Bonham Carter.
- Analyzed highest and lowest-rated movies in the Harry Potter franchise featuring Daniel Radcliffe.

## Outcome
This project highlights the ability to:
- Set up distributed computing environments using AWS EMR.
- Perform large-scale data analysis with PySpark.
- Clean, transform, and extract meaningful insights from raw data.
- Create data visualizations for storytelling and communication.

## Status
✅**Completed** — Final analysis and formatting are completed.

## Author
Hao Le  
[LinkedIn](https://linkedin.com/in/haonle) | haole7124@gmail.com

---

**Note:** This project was completed as part of an academic assignment for the Big Data Technologies course at Baruch College.
