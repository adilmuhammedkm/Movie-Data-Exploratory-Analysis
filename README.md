# Movie Data Exploratory Analysis

An exploratory data analysis project that investigates movie production trends, audience engagement, popularity, genres, runtime, budget, and revenue to identify patterns and factors associated with movie performance.

---

## Project Overview

The movie industry generates large amounts of data related to production, audience ratings, popularity, financial investment, and revenue.

This project performs an end-to-end exploratory data analysis of movie data using Python to uncover meaningful patterns and answer important business questions related to movie performance.

The analysis focuses on understanding how movie production has changed over time, how audience engagement relates to popularity, which genres attract greater audience interest, whether runtime influences popularity, and whether higher production budgets are associated with higher revenue.

---

## Objectives

- Analyze movie production trends over time
- Investigate the relationship between audience engagement and movie popularity
- Compare average popularity across major movie genres
- Examine the relationship between movie runtime and popularity
- Analyze the relationship between production budget and revenue
- Translate analytical findings into meaningful business questions and insights

---

## Dataset

The project uses a movie dataset containing information related to:

- Movie title and tagline
- Release date and release year
- Genres
- Budget
- Revenue
- Vote count
- Vote average
- Popularity
- Runtime
- Cast and crew information
- Production companies
- Production countries
- Original language

The dataset is stored in:

```text
data/movies_complete.csv
```

The analysis also accounts for the incomplete final year in the dataset when examining movie production trends.

---

## Tools & Technologies

- **Python**
- **Pandas** – Data cleaning, transformation, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Exploratory analysis and documentation

---

## Analysis Performed

### 1. Movie Production Trends

Analyzed the number of movies released across different years to understand how movie production has changed over time.

**Finding:** Movie production increased substantially over the years, with particularly strong growth from the 1990s onward.

---

### 2. Audience Ratings and Popularity

Investigated the relationship between average movie ratings and popularity.

**Finding:** Average rating alone does not strongly explain movie popularity. Movies with similar ratings can have substantially different popularity levels.

---

### 3. Audience Engagement and Popularity

Analyzed the relationship between vote count and movie popularity.

**Finding:** Movies with higher vote counts generally tend to have higher popularity, indicating a clear positive association between audience engagement and popularity.

---

### 4. Movie Genres and Popularity

Compared average popularity across major movie genres.

**Finding:** Adventure movies show the highest average popularity among the major genres analyzed, followed by Fantasy and Science Fiction.

---

### 5. Movie Runtime and Popularity

Examined whether movie duration is strongly associated with audience popularity.

**Finding:** The relationship between runtime and popularity appears weak and highly dispersed. Most movies fall within approximately 60–180 minutes, but popularity varies substantially within this range.

---

### 6. Movie Budget and Revenue

Investigated whether higher production budgets are associated with higher movie revenue.

**Finding:** Movies with higher production budgets generally tend to generate higher revenues. However, substantial variation exists, particularly among lower-budget movies, showing that budget alone does not guarantee strong revenue performance.

---

## Business Questions

The analysis addresses the following business questions:

### Q1. How has movie production changed over time?

Movie production increased substantially over the years, with particularly rapid growth from the 1990s onward.

### Q2. Does audience engagement influence movie popularity?

Movies with higher vote counts generally tend to have higher popularity, showing a clear positive relationship between audience engagement and popularity.

### Q3. Which movie genres attract the highest audience interest?

Adventure movies have the highest average popularity among the major genres analyzed, followed by Fantasy and Science Fiction.

### Q4. Does movie runtime strongly influence popularity?

Runtime does not appear to be a strong indicator of popularity. Most movies fall within approximately 60–180 minutes, while popularity varies considerably within this range.

### Q5. Does a higher movie budget lead to higher revenue?

Higher-budget movies generally tend to generate higher revenues, although budget alone does not guarantee strong commercial performance.

---

## Key Insights

- **Movie production has increased significantly over time**, with particularly strong growth in the number of releases from the 1990s onward.
- **Audience engagement is strongly associated with movie popularity**, with movies receiving more votes generally achieving higher popularity.
- **Adventure movies show the highest average popularity**, followed by Fantasy and Science Fiction.
- **Movie runtime is not a strong indicator of popularity**, with most movies falling within approximately 60–180 minutes.
- **Movie budget has a positive relationship with revenue**, although financial investment alone does not guarantee commercial success.
- **Movie performance is influenced by multiple factors** rather than a single variable.

---

## Visualizations

The project includes visualizations for the major analytical findings.

### Production Over Time

![Production Over Time](screenshots/Production%20Over%20Time.png)

### Ratings vs Popularity

![Ratings vs Popularity](screenshots/Ratings%20vs%20Popularity.png)

### Audience Engagement vs Popularity

![Audience Engagement vs Popularity](screenshots/Audience%20Engagement%20vs%20Popularity.png)

### Genres vs Popularity

![Genres vs Popularity](screenshots/Genres%20vs%20Popularity.png)

### Runtime vs Popularity

![Runtime vs Popularity](screenshots/Runtime%20vs%20Popularity.png)

### Budget vs Revenue

![Budget vs Revenue](screenshots/Budget%20vs%20Revenue.png)

### Business Questions

![Business Questions](screenshots/Business%20Questions.png)

### Key Insights & Conclusion

![Key Insights and Conclusion](screenshots/Key%20Insights%20%2B%20Conclusion.png)

---

## Project Structure

```text
Movie-Data-Exploratory-Analysis/
│
├── archive/
│   ├── EDA ON SAMPLE DATASET.ipynb
│   └── Handling Missing Values and Data...
│
├── data/
│   └── movies_complete.csv
│
├── notebooks/
│   └── 01_Movie_EDA.ipynb
│
├── screenshots/
│   ├── Audience Engagement vs Popularity.png
│   ├── Budget vs Revenue.png
│   ├── Business Questions.png
│   ├── Genres vs Popularity.png
│   ├── Key Insights + Conclusion.png
│   ├── Production Over Time.png
│   ├── Ratings vs Popularity.png
│   └── Runtime vs Popularity.png
│
└── README.md
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/adilmuhammedkm/Movie-Data-Exploratory-Analysis.git
```

### 2. Navigate to the project

```bash
cd Movie-Data-Exploratory-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

```text
notebooks/01_Movie_EDA.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

---

## Main Notebook

The complete exploratory analysis is available in:

```text
notebooks/01_Movie_EDA.ipynb
```

The notebook contains data exploration, analysis, visualizations, interpretations, business questions, key insights, and the final conclusion.

---

## Conclusion

This exploratory analysis demonstrates that movie performance is influenced by multiple factors rather than a single variable.

Movie production has increased substantially over time, while audience engagement shows a clear positive association with movie popularity. Genre is also associated with differences in audience interest, with Adventure, Fantasy, and Science Fiction showing higher average popularity among the major genres analyzed.

In contrast, movie runtime shows a weak relationship with popularity, indicating that longer movies do not necessarily attract greater audience attention. Movie budget has a positive relationship with revenue, suggesting that higher financial investment can increase earning potential, although budget alone does not guarantee commercial success.

Overall, the analysis provides useful data-driven insights into movie popularity and revenue performance and demonstrates the application of Python-based exploratory data analysis to a real-world dataset.

---

# Author

**Adil Muhammed K M**

- GitHub: https://github.com/adilmuhammedkm
- LinkedIn: https://www.linkedin.com/in/adilmuhammedkm
