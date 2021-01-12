# Anime-Analysis-and-Modeling
Rectently, animes are becoming more and more popular since some amazing anime movies came out. This interests us to do some analysis and modeling on people who are watching animes.

The dataset comes from Kaggle [MyAnimeList Dataset](https://www.kaggle.com/azathoth42/myanimelist).

There are three datasets in it:


*   `UserList` - contains all user data, i.e. username, age, gender.
*   `AnimeList` - contains all anime data, i.e. anime name, studio, genre
*   `UserAnimeList` - contains scores given by users to animes and other user scoring statistics

## Data Source: 
[MyAnimeList Dataset](https://www.kaggle.com/azathoth42/myanimelist) - This dataset contains information about Anime and users on MyAnimeList.net who watch it. It contains information about users (gender, location, birth date etc.), about anime (airing date, genres, producer…) and anime lists. 
+ AnimeList.csv contains list of anime, with title, title synonyms, genre, studio,producer, duration, rating, score, airing date, episodes, source (manga, light novel etc.) and many other important data
+ UserList.csv contains information about users who watch anime, namely username, registration date (join_date), last online date, birth date, gender, location, and lots of aggregated values from their anime lists
+ UserAnimeList.csv contains anime lists of all users. Per each record, here is username, anime ID, score, status and timestamp when was this record last updated
