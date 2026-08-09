# Movie Data Exploratory Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) of a movie dataset containing information about movies, including release dates, genres, languages, budgets, revenues, ratings, popularity, runtime, cast, crew, production companies, and directors.

The analysis focuses on understanding the structure and quality of the dataset, handling missing and irrelevant data, preparing fields for analysis, and answering business-style questions through Python-based exploratory analysis.

## Objectives

- Understand the structure and characteristics of the movie dataset
- Identify missing values and assess their impact
- Perform data cleaning and preparation
- Analyze movie ratings, popularity, revenue, budget, and runtime
- Explore movie production companies, directors, languages, and genres
- Investigate relationships and patterns within the dataset
- Answer practical analytical questions using Pandas

## Dataset

The dataset contains **44,691 movie records and 19 columns**.

Key fields include:

- Movie ID
- Title
- Tagline
- Release Date
- Genres
- Original Language
- Budget
- Revenue
- Production Companies
- Production Countries
- Vote Count
- Vote Average
- Popularity
- Runtime
- Cast
- Cast Size
- Crew Size
- Director

The dataset contains substantial missing data in several fields, particularly budget, revenue, collection information, and taglines. Missing-value analysis was therefore an important part of the data preparation process.

## Analysis Performed

### 1. Dataset Exploration

- Inspected the first records
- Examined dataset dimensions
- Reviewed data types
- Generated descriptive statistics
- Examined numerical distributions

### 2. Data Quality Analysis

- Identified null values
- Calculated percentage of missing values by column
- Investigated potentially irrelevant columns
- Examined duplicate records
- Reviewed data consistency

### 3. Data Cleaning

The analysis includes:

- Removing selected irrelevant columns
- Renaming columns for consistency
- Converting release dates into a consistent datetime format
- Examining missing-value handling approaches
- Creating cleaned DataFrame versions for further analysis

### 4. Exploratory Analysis

The project investigates questions such as:

- Which production company's movie generated the highest revenue?
- Which movie has the highest vote average?
- Which movie has the highest vote count?
- Which action movie has the lowest budget?
- Which director has the best vote average?
- How many English-language movies are present?
- How many movies were released in 1995?
- Which movie has the highest popularity?
- Which movie has the shortest runtime?
- Which movie has the lowest cast and crew size?
- What is the tagline of the movie with the lowest vote average?
- What are the production countries associated with a specific movie?

## Key Data Quality Observations

The dataset contains significant levels of missing information.

Examples from the initial analysis include:

- `tagline` — approximately 54.6% missing
- `belongs_to_collection` — approximately 90.0% missing
- `budget_musd` — approximately 80.2% missing
- `revenue_musd` — approximately 83.5% missing
- `production_companies` — approximately 25.4% missing
- `production_countries` — approximately 13.1% missing

This highlights the importance of evaluating data completeness before performing analysis.

## Descriptive Statistics

Selected numerical statistics from the dataset:

| Metric | Mean | Median |
|---|---:|---:|
| Budget (M USD) | 21.67 | 8.20 |
| Revenue (M USD) | 68.97 | 16.87 |
| Vote Count | 111.65 | 10 |
| Vote Average | 6.00 | 6.10 |
| Popularity | 2.96 | 1.15 |
| Runtime (minutes) | 97.57 | 95 |
| Cast Size | 12.48 | 10 |
| Crew Size | 10.31 | 6 |

These statistics illustrate substantial variation across financial, rating, popularity, runtime, and production-related attributes.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Structure

```text
Movie-Data-Exploratory-Analysis/
│
├── data/
│   └── movies_complete.csv
│
├── notebooks/
│   └── 01_Movie_EDA.ipynb
│
├── screenshots/
│   └── analysis visualizations
│
├── archive/
│   ├── EDA ON SAMPLE DATASET.ipynb
│   └── Handling Missing Values and Data Visualisation.ipynb
│
└── README.md
```

## Analysis Workflow

```text
Raw Movie Dataset
       ↓
Dataset Exploration
       ↓
Data Quality Assessment
       ↓
Missing Value Analysis
       ↓
Data Cleaning & Preparation
       ↓
Descriptive Statistics
       ↓
Exploratory Analysis
       ↓
Analytical Questions
       ↓
Insights & Visualizations
```

## Outcome

This project demonstrates practical experience with the core stages of exploratory data analysis:

- Data inspection
- Data quality assessment
- Missing-value analysis
- Data cleaning
- Feature preparation
- Descriptive statistics
- Exploratory analysis
- Data visualization
- Question-driven analysis

The project provides a foundation for understanding movie-industry data and extracting meaningful patterns from a large real-world dataset.

## Future Improvements

Potential extensions include:

- Genre-level analysis using normalized genre data
- Revenue and budget profitability analysis
- Time-series analysis of movie releases
- Director and production-company performance analysis
- Correlation analysis between popularity, ratings, revenue, and budget
- Interactive visualization dashboard
- Advanced statistical analysis
- Predictive modeling for movie ratings or revenue
