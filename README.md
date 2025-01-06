# Netflix Content Analysis Project

## Description
This repository contains a comprehensive exploratory data analysis (EDA) of Netflix's dataset, focusing on trends, content distribution, and genre insights. The project involves cleaning the raw data, generating meaningful insights, and visualizing the results using Power BI and Python.

---

## Features
- **Data Cleaning**: Handling missing values, standardizing formats, and deriving new columns for analysis.
- **Visualizations**: Interactive dashboards created using Power BI to uncover trends in content availability.
- **Insights**: Insights into movies vs. TV shows, genre distribution, ratings, and global content distribution.

---

## Project Structure
```
Netflix_Content_Analysis/
├── Data/
│   ├── netflix_raw.csv          # Raw dataset
├── PowerBI/
│   ├── Netflix_Dashboard.pbix   # Power BI dashboard file
│   ├── Dashboard_Screenshot.png # Screenshot of the dashboard
├── README.md                    # Project description and instructions

```

---

## Dashboard Preview

![Netflix Dashboard](PowerBI/Dashboard_Screenshot.png)

**Features of the Dashboard:**
- Total number of shows, movies, and TV shows.
- Distribution of content ratings.
- Count of shows by country.
- Movies vs. TV shows comparison.
- Yearly trend of releases.
- Genre selection filters.

---

## Dataset

The dataset used in this project was sourced from [Kaggle Netflix Dataset](https://www.kaggle.com/shivamb/netflix-shows).

### Original Dataset Columns:
- `show_id`: Unique ID for each title.
- `type`: Movie or TV Show.
- `title`: Title of the content.
- `director`: Director of the content.
- `cast`: List of actors.
- `country`: Country of origin.
- `date_added`: Date when the title was added to Netflix.
- `release_year`: Year of release.
- `rating`: Content rating (e.g., PG-13, TV-MA).
- `duration`: Duration of the movie or number of seasons.
- `listed_in`: Genres of the content.
- `description`: Summary of the title.

### Cleaned Dataset Enhancements:
- Filled missing values in `director`, `cast`, and `country` with "Unknown."
- Extracted `year_added` from `date_added`.
- Split `duration` into `runtime_minutes` (for movies) and `seasons` (for TV shows).

---

## Tools and Technologies Used
- **Power BI**: For interactive dashboard creation.
- **GitHub**: For version control and project sharing.

---


## Insights from the Analysis
- **Content Types**:
  - Total Titles: 8808
  - Movies: 6131
  - TV Shows: 2676
- **Release Trends**:
  - The highest number of releases occurred after 2010.
  - Movies dominate the catalog compared to TV shows.
- **Global Distribution**:
  - The USA contributes the highest number of titles.
- **Ratings**:
  - TV-MA is the most common content rating.
- **Genres**:
  - Popular genres include International Movies, Dramas, and Comedies.

---

## Contributions
Contributions are welcome! Please fork the repository and create a pull request with your enhancements or suggestions.

---

