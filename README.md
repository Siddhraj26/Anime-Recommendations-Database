# Anime Recommendation System
# Anime-Recommendations-Database

Python-based Anime Recommendations Database cleaning and visualization project exploring anime ratings, genres, popularity, and user rating patterns.

---

## Project Overview

This project analyzes the **Anime Recommendations Database** from Kaggle, which contains recommendation data from about 76,000 users at [myanimelist.net](https://myanimelist.net). Using Python, the raw data is cleaned, explored, and visualized to uncover patterns in anime ratings, genres, types, episode counts, and community popularity. It also lays the groundwork for a basic genre-based recommendation approach.

**Course:** Data Cleaning, Exploratory Analysis and Visualization
**University:** Indus University | B.Tech CSE-G | Semester V | 2026-27

## Team

| Name | Enrollment No. |
| --- | --- |
| Siddhrajsinh Chauhan | IU2541231877 |
| Rushil Patel | - |

## Dataset

- **Source:** [Anime Recommendations Database (Kaggle)](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database)
- **Files:**
  - `anime.csv` - `anime_id`, `name`, `genre`, `type`, `episodes`, `rating`, `members`
  - `rating.csv` - `user_id`, `anime_id`, `rating` (`-1` means watched but not rated)

## Objectives

- Clean missing, unrated, and duplicate records
- Identify the highest-rated and most popular anime
- Analyze the distribution of ratings, types, and genres
- Study relationships between rating, members, and episode count
- Build a basic genre-based recommendation approach using similarity measures

## Repository Structure

```
Anime-Recommendations-Database/
│
├── 01_data_cleaning.ipynb        # Data loading, cleaning and preprocessing
├── 02_visualizations.ipynb       # Exploratory analysis and plots
├── 1_top10_rated.png
├── 2_rating_distribution.png
├── 3_rating_vs_members.png
├── 4_type_distribution.png
├── 5_top_genres.png
├── 6_episodes_vs_rating.png
├── 7_most_popular.png
├── anime_cleaned.csv             # Cleaned dataset
└── README.md
```

## Visualizations

| # | Plot | Type | Purpose |
| --- | --- | --- | --- |
| 1 | Top 10 Anime by Average Rating | Bar Chart | Compare the highest-rated anime |
| 2 | Anime Rating Distribution | Histogram | Find the most common rating range |
| 3 | Rating vs Members | Scatter Plot | Relationship between rating and popularity |
| 4 | Anime Type Distribution | Bar/Pie Chart | Spread across TV, Movie, OVA, Special, ONA, Music |
| 5 | Top Genres by Number of Anime | Bar Chart | Most represented genres |
| 6 | Episodes vs Rating | Scatter Plot | Does episode count affect rating? |
| 7 | Most Popular Anime by Members | Bar Chart | Anime with the largest community following |

## Tech Stack

- **Python**
- **Pandas** - data loading, cleaning, and analysis
- **NumPy** - numerical operations
- **Matplotlib** - visualizations
- **Seaborn** - statistical plots
- **Scikit-learn** - genre vectorization and similarity
- **Google Colab / Jupyter Notebook** - development environment
- **Git & GitHub** - version control and collaboration

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/Siddhraj26/Anime-Recommendations-Database.git
   cd Anime-Recommendations-Database
   ```
2. Install the dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Download `anime.csv` and `rating.csv` from the [Kaggle dataset](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database) and place them in the project folder.
4. Run the notebooks in order:
   - `01_data_cleaning.ipynb`
   - `02_visualizations.ipynb`

## Key Findings

_To be added after the analysis is complete._

## Expected Outcome

Meaningful insights into anime ratings, popularity, genres, types, and user rating behavior, presented through clear visualizations and a basic recommendation approach, using a real-world entertainment dataset.

## Contributors

- [Siddhrajsinh Chauhan](https://github.com/Siddhraj26)
- Rushil Patel
