# Spotify Trends Analysis

An end-to-end data analytics project exploring trends in Spotify music data using Python, Pandas, Matplotlib, and exploratory data analysis techniques. This project investigates what makes songs popular, analyzes genre trends, visualizes relationships between musical features, and will later include feature engineering, machine learning, and an interactive dashboard.

---

## Project Status

🚧 In Progress

Current Progress:
- ✅ Data Loading
- ✅ Exploratory Data Analysis (EDA)
- ✅ Data Visualization
- ⏳ Data Cleaning
- ⏳ Feature Engineering
- ⏳ Business Insights Report
- ⏳ Machine Learning
- ⏳ Interactive Dashboard (Streamlit)

---

## Dataset

**Dataset:** Spotify Tracks Dataset

Contains approximately **114,000 Spotify tracks** with audio features and metadata.

Features include:

- Track Name
- Artist
- Album
- Genre
- Popularity
- Danceability
- Energy
- Loudness
- Tempo
- Acousticness
- Speechiness
- Instrumentalness
- Valence
- Duration
- Explicit
- Time Signature
- and more...

---

## Project Goals

The objectives of this project are to:

- Explore the Spotify dataset using exploratory data analysis
- Discover trends in song popularity
- Compare popularity across genres
- Visualize relationships between audio features
- Perform data cleaning and feature engineering
- Build predictive machine learning models
- Create an interactive dashboard for exploring the dataset

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git
- GitHub

**Planned**

- Scikit-Learn
- Plotly
- Streamlit

---

## Key Findings

Current insights include:

- Average song popularity is around **33**
- Most songs have moderate popularity rather than extremely high popularity
- Popularity has very weak linear correlation with individual audio features
- Energy and loudness have a strong positive relationship
- Energy and acousticness have a strong negative relationship
- The most common genre in the dataset is **acoustic**
- The most frequent artist is **The Beatles**
- The most popular genre by average popularity is **pop-film**

More insights will be added as the project progresses.

---

## Visualizations

Current visualizations include:

- Popularity Distribution Histogram
- Energy vs Popularity Scatter Plot
- Correlation Heatmap
- Top 10 Genres by Average Popularity

Visualizations are stored inside:

```
images/
```

---

## Project Structure

```text
SpotifyTrendsAnalysis/
│
├── data/
│   ├── raw/
│   │   └── spotify_tracks_dataset.csv
│   └── processed/
│
├── images/
│   ├── histogram_popularity.png
│   ├── scatter_energy_popularity.png
│   ├── correlation_heatmap.png
│   └── top10_genres.png
│
├── notebooks/
│   └── exploration.ipynb
│
├── reports/
│   └── analysis_report.md
│
├── src/
│   ├── cleaning.py
│   ├── analysis.py
│   ├── visualization.py
│   └── utils.py
│
├── README.md
└── requirements.txt
```

---

## Future Work

Upcoming improvements include:

- Data Cleaning
- Feature Engineering
- Business Analysis Report
- Predictive Machine Learning Model
- Streamlit Dashboard
- Improved Visualizations using Plotly
- Interactive Filters
- Model Evaluation

---

## Author

**ShyLenny**
