🎌 Anime and Manga EDA — Ratings, Popularity & Recommendation System
📘 Overview

This project explores Anime and Manga datasets to uncover trends in ratings, popularity, and genres, and includes a content-based recommendation system.
It combines Python-based Exploratory Data Analysis (EDA) with a Power BI Dashboard for interactive visualization and storytelling.

🧠 Objectives

Perform deep EDA on anime & manga datasets to find meaningful insights.

Analyze relationships between ratings, popularity, genres, and release years.

Identify top genres, studios, and seasonal trends.

Build a recommendation system that suggests similar anime/manga based on user preferences.

Present findings visually using Power BI.

🗂️ Files Included
File	Description
Anime_Manga_Rating-Popularity-Trend_Analysis.ipynb	Jupyter Notebook for full EDA and recommendation system implementation
Anime and Manga Dashboard.pbix	Power BI dashboard for interactive visual insights
README.md	Documentation file for project structure and summary
🧰 Tools & Libraries Used
Python (EDA, Recommendation System, and Data Cleaning)

pandas, numpy – data handling & preprocessing

matplotlib, seaborn, plotly – visualization

wordcloud – for common genre/title visualization

scikit-learn – for similarity computation & recommendation system

datetime – for time-based analysis

Power BI (Dashboard Creation)

Used Power BI to build an interactive dashboard highlighting genre popularity, release trends, and ratings distribution.

🤖 Recommendation System

A content-based filtering system using cosine similarity and TF-IDF vectorization was implemented to recommend anime or manga based on:

Genre similarity

Rating patterns

Popularity and type (TV, Movie, Manga)

Example:

If a user likes Attack on Titan, the system recommends titles with similar genres and fan engagement metrics.

🔍 Key Insights

Action, Romance, and Fantasy remain top genres across both anime and manga.

Ratings peaked between 2014–2019, coinciding with the global anime boom.

Some series are extremely popular but not highly rated, showing audience diversity.

Studios like Kyoto Animation and Ufotable consistently produce top-rated titles.

Recommendation results align closely with community-favorite suggestions.

📊 Visual Highlights

Heatmap: Ratings vs. Popularity correlation

Word Cloud: Top genres and keywords

Yearly Trend Line: Releases over time

Boxplots: Distribution of ratings and popularity

Power BI Dashboard: Interactive visuals with slicers for genre, year, and type

🚀 How to Run

Clone the repository:

git clone https://github.com/<your-username>/Anime-and-Manga-EDA.git
cd Anime-and-Manga-EDA


Install dependencies:

pip install pandas numpy matplotlib seaborn plotly wordcloud scikit-learn


Open the Jupyter Notebook:

jupyter notebook Anime_Manga_Rating-Popularity-Trend_Analysis.ipynb


(Optional) Open Power BI file:

Launch Power BI Desktop

Open Anime and Manga Dashboard.pbix

💡 Future Enhancements


Integrate live data using MyAnimeList API.

Deploy recommendation system as a web app (Streamlit / Flask).

🧑‍💻 Author

Ch. Hemanth Sai
B.E – Artificial Intelligence & Data Science (CBIT)
