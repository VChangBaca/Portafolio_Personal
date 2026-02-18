# Spotify Songs Extractor

Automated data extraction pipeline that retrieves playlist information from Spotify and enriches it with artist metadata and country origin using external APIs.

## Objective

Build a reproducible workflow to extract, enrich, and export structured music data from Spotify playlists.

## Process

1. Authenticate with Spotify API using Spotipy.
2. Extract all tracks from a playlist.
3. Retrieve artist genres and metadata.
4. Query MusicBrainz API to obtain artist country.
5. Clean and structure the dataset.
6. Export results to Excel.

## Technologies

- Python
- Spotipy (Spotify API)
- Requests (REST API)
- Pandas
- Data Processing

## Output

Structured dataset containing:

- Song name
- Artists
- Genres
- Duration (seconds)
- Artist country

## Skills Demonstrated

- API integration
- Data engineering workflows
- Automated data collection
- Data cleaning and transformation

## Author

Víctor Chang Baca
