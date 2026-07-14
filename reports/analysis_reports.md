# Spotify Trends Analysis

## Phase 1: Exploratory Data Analysis (EDA)

### Dataset Overview

- Total Songs: 114,000
- Total Features: 21
- Missing Values: 3
- Unique Artists: 31,437
- Most Common Artist: The Beatles
- Most Common Genre: Acoustic

---

## Popularity Analysis

### Findings

- Average popularity: 33.24
- Median popularity: 35
- Maximum popularity: 100
- Minimum popularity: 0

### Observation

Most songs have relatively low to medium popularity. Only a small number of songs achieve the maximum popularity score.

---

## Correlation Analysis

### Findings

- Loudness has the highest positive correlation with popularity (~0.05).
- Instrumentalness has the strongest negative correlation (~-0.09).

### Observation

Audio features alone do not strongly explain a song's popularity.

---

## Genre Analysis

### Findings

Highest Average Popularity:
- Pop-film

Lowest Average Popularity:
- Iranian

Top Genres:
- Pop-film
- K-pop
- Chill
- Sad
- Grunge

### Observation

Some niche genres have surprisingly high average popularity.

---

## Key Takeaways

- The dataset is clean and contains very few missing values.
- Popularity is not normally distributed.
- Energy has almost no relationship with popularity.
- Energy and loudness are strongly positively correlated.
- Energy and acousticness are strongly negatively correlated.
- Genre appears to be more informative than individual audio features.