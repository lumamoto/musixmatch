# Musixmatch Python API Tutorial for Developers

Use python to interact with the Musixmatch API for song lyrics

### Prerequisites

* [Python3](http://www.python.org/downloads)
* [Musixmatch Developer Account](https://developer.musixmatch.com/)

### Installing

1. Download and put the two python files in the same folder somewhere

2. Install requests from terminal

```
sudo pip3 install requests
```

3. Enter your API key inside of lyrics_api.py

### How To Use

1. Run lyrics.py

2. Select "MENU OPTION 1 - Call one of the API methods with parameters and see JSON"

3. Select API Method 4: track.search

4. Enter the following parameters:
- To set genre to rap/hip hop:
    - 5: &f_music_genre_id=18
- For songs released between January 1, 2000 to December 31, 2009 (Format is YYYYMMDD):
    - 11: &f_track_release_group_first_release_date_min=20000101
    - 12: &f_track_release_group_first_release_date_max=20091231
- For songs in English:
    - 6: &f_lyrics_language=en
- To get 100 results at a time:
    - 10: &page_size=100
- To get another set of 100 songs:
    -  9: &page=2 (3, 4, 5, etc.)

### Menu Options

1. Call one of the API methods with parameters and see JSON data
2. EXAMPLE: Search for the lyrics of a song
3. Exit

## Built With

* [Atom](http://www.atom.io) - The web framework used


## Authors

* **Ian Annase**
