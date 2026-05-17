# Spotify Tracks Analysis 🎵
Exploratory data analysis of 114,000+ Spotify tracks across 114 genres, 
built with Python, Pandas, Matplotlib and Seaborn.

## Dataset
[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) by Maharshi Pandya — Kaggle
114,000 rows · 21 columns · 114 unique genres

## Tools
Python · Pandas · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook

## Analyses Completed
* Top 10 genres by average popularity
* Top 10 genres by average energy
* Top 10 genres by average danceability
* Correlation heatmap between audio features
* Top 20 most popular songs (deduplicated)
* Happiest vs saddest genres by valence
* Valence vs popularity by genre (scatter plot)
* Song duration vs popularity (box plot)
* Explicit vs clean tracks — popularity comparison overall and by genre
* Genre clustering with K-Means — 4 audio profiles identified
* Audio profiles of the 6 most popular artists — radar chart comparison
* Popularity distribution across the dataset
* BPM distribution across the top 10 most popular genres

## Key Findings
* Pop-film and k-pop dominate in popularity, while metal subgenres lead in energy
* Energy and loudness are strongly correlated (0.76); acousticness and energy inversely (-0.73)
* Popularity shows almost zero correlation with any audio feature
* Songs between 3–4 minutes tend to be the most popular on Spotify
* Melancholic genres like "sad" and "chill" are surprisingly popular
* Explicit tracks are slightly more popular on average, but the gap varies heavily by genre
* Hip-hop clean tracks outperform explicit ones — contrary to common assumption
* K-Means identified 4 natural genre clusters: Rhythmic & Dance, Melodic & Emotional, High Energy & Intensity, Calm & Atmospheric
* The 6 most popular artists have completely different audio profiles — no single formula for success
* 14% of tracks have zero popularity — the dataset is heavily skewed toward unknown music
* BPM is surprisingly consistent across the top 10 most popular genres

## Conclusions
Popularity on Spotify cannot be predicted from audio features alone. What makes 
a song successful goes far beyond how it sounds — artist fame, playlist placement, 
cultural trends and timing likely matter far more than any measurable audio feature.

## Status
✅ Project completed
