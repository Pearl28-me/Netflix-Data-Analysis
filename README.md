# Netflix Data Analysis

## Project Overview
This project explores and analyzes Netflix's content dataset to uncover trends in movies and TV shows, including genres, countries, ratings, and release patterns.
The goal is to understand how Netflix content is distributed and how it has evolved over time.


## Dataset
* Netflix Movies and TV Shows dataset
* Contains information on titles, genres, countries, ratings, and duration


## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn


## Analysis Performed

* Data cleaning and preprocessing
* Handling missing values
* Splitting multi-category fields (genres, countries)
* Feature engineering (duration, decade, type)
* Exploratory data analysis (EDA)
* Visualization of trends and distributions


## 📊 Key Visualizations & Insights

### Genre Distribution
![Genre Distribution](images/chart1_genre_counts_bar.png)
Drama and international content dominate Netflix, showing a strong focus on globally appealing content.


### Top 10 Countries
![Top Countries](images/chart2_top10_countries.png)
The United States produces the highest number of titles, followed by other major content-producing countries.


### Rating Breakdown by Type
![Rating vs Type](images/chart3_stacked_rating_type.png)
Movies and TV shows differ in rating distributions, reflecting different audience targets.


### Movie vs TV by Genre
![Genre Type](images/chart4_100pct_genre_type.png)
Some genres are dominated by movies, while others are more common in TV shows.


### Content Over Decades
![Decade](images/chart7_titles_per_decade.png)
Content production has significantly increased in recent decades, especially after 2000.


### Top Directors
![Directors](images/chart8_top_directors.png)
A few directors contribute multiple titles, indicating recurring collaborations.


### Content Added Over Time
![Year Added](images/chart9_titles_added_by_year.png)
Netflix content grew rapidly in recent years, reflecting platform expansion.


### Movie Duration Analysis
![Duration](images/boxplot_durations.png)
Most movies fall within a typical duration range, with a few extreme outliers.


## Key Insights

* Drama and international genres dominate Netflix content
* The U.S. is the leading content producer
* Netflix has rapidly expanded its library over time
* Movies and TV shows serve different audience segments
* Most movies follow a standard duration range


## 📁 Project Structure
netflix-data-analysis/
│
├── data/
├── images/
├── notebooks/
     └──Netflix-data-analysis.ipynb
└── README.md


## How to Run

Bash
pip install -r requirements.txt
jupyter notebook


## Future Work

* Build recommendation system
* Perform clustering on content types
* Predict popularity or ratings


**Korang Pearl Antwi**
