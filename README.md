# Media-Catalogue-Python-OOP-Project-FreeCodeCamp-
A simple object-oriented Python project that models a media catalogue containing movies and TV series. It demonstrates inheritance, custom exceptions, and data validation.

# Features

- Add Movies and TV Series to a catalogue
- Validate input data (title, year, director, duration)
- Separate listing of Movies and TV Series
- Custom exception handling (`MediaError`)
- Clean object-oriented structure


# Classes Overview

### Movie
Represents a single movie.

Attributes:
- title
- year
- director
- duration

### TVSeries (inherits from Movie)
Represents a full TV series.

Additional attributes:
- seasons
- total_episodes

### MediaCatalogue
Stores and manages a list of media items.

Methods:
- add(item) → adds Movie or TVSeries
- get_movies() → returns only Movie objects
- get_tv_series() → returns only TVSeries objects
- __str__() → formatted catalogue output

### MediaError
Custom exception raised when invalid media is added.

# Example Output

Media Catalogue (4 items):

=== MOVIES ===
1. The Matrix (1999) - 136 min, The Wachowskis
2. Inception (2010) - 148 min, Christopher Nolan

=== TV SERIES ===
1. Scrubs (2001) - 9 seasons, 182 episodes, 24 min avg, Bill Lawrence
2. Breaking Bad (2008) - 5 seasons, 62 episodes, 47 min avg, Vince Gilligan
