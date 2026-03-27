# Clustering-Spotify-Songs-Using-Audio-Features-KMeans-Approach-
Clustering Spotify Songs Using Audio Features (KMeans Approach)
# 🎧 Recreating Spotify “Made For You” Playlists with Machine Learning

## Project Overview
Spotify gives users weekly playlists — but how are they created?

In this project, I built a simplified machine learning model to explore how playlists can be generated using only audio features.

This is NOT how Spotify actually works, but a simplified approach using clustering.

---

## Dataset
- Public Spotify dataset (10,000 songs)
- Features used:
  - danceability
  - energy
  - tempo
  - valence
  - loudness
  - speechiness
  - liveness

---

## Approach

### 1. Data Cleaning
- Removed non-numerical columns (name, artists)

### 2. Feature Scaling
- Standardized features using `StandardScaler`

### 3. Clustering
- Applied KMeans clustering
- Used Elbow Method to find optimal number of clusters

### 4. Dimensionality Reduction
- Applied PCA to visualize data in lower dimensions

---

## Key Insight

- Songs can be grouped based on audio features alone
- Clusters represent different "vibes" → similar to playlists
- Outliers reveal interesting edge cases (e.g. silent track)

---

## Tools Used
- Python
- Pandas
- Scikit-learn
- Plotly
- Matplotlib / Seaborn

---

## Disclaimer

This is a simplified experiment based on publicly available data.

No user behaviour, no personalization — just patterns in the data.

No companies or individuals were harmed or offended in this experiment.

Just a few clusters… and one silent track.

---

## Contact
erdi ozyurt march 2026
