# Spotify Tracks Analysis with Python

Third-year computer science and networks project (EMSI Marrakech).

## Goal
Analyze a dataset of 114,000 Spotify tracks to understand which genres are the most
danceable and what explains the popularity of a song.

## Data
- Source: [Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/yashdev01/spotify-tracks-dataset) (author: Yash)
- 114,000 tracks, 114 genres, 1,000 tracks per genre
- Main columns: danceability, energy, valence, tempo, popularity, track_genre
  
  
## Tools
Python, pandas, matplotlib, Google Colab

## Questions and results
1. **Which genres are the most danceable?** Kids, chicago-house and reggaeton come first.
2. **Do audio features explain popularity?** No. All correlations with popularity are close to 0 (the highest is loudness, at 0.05).
3. **Which genres are the most popular?** Pop-film, k-pop and chill lead, well above the overall average (about 33).

## Conclusion
A track's genre explains its popularity better than its audio features.
The most danceable genres are not the most popular ones.

## Limitations
- Correlation does not mean causation.
- The dataset has 1,000 tracks per genre, so it does not reflect what people actually listen to.
- Popularity also depends on factors missing here (artist, marketing, playlists, release date).

## Files
`analyse_spotify.ipynb`: the full notebook with the code and charts.
