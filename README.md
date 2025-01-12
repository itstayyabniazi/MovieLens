# MovieLens
MovieLens dataset Analysis available on [MovieLens](https://grouplens.org/datasets/movielens/) using Python, Pandas, and Matplotlib. <br>
Created a Jupyter Notebook for code, and visualizations of the Analysis performed.

## My Analysis Includes <br>
- Data Cleaning and Preparation
- Data Exploration and Transformation
- Data Aggregation and Group Operations
- Interactive Visualization
- Advanced Data Wrangling


## Badges
![GitHub last commit](https://img.shields.io/github/last-commit/itstayyabniazi/MovieLens)
![MIT License](https://img.shields.io/badge/Version-0.5-blue) <br>
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Dataset Overview

This dataset (ml-32m) describes 5-star rating and free-text tagging activity from a movie recommendation service. It contains 32000204 ratings and 2000072 tag applications across 87585 movies. These data were created by 200948 users between January 09, 1995 and October 12, 2023. This dataset was generated on October 13, 2023.

The data are contained in the files `links.csv`, `movies.csv`, `ratings.csv` and `tags.csv`. More details about the contents and use of all these files are bellow.

### Ratings (ratings.csv)
All ratings are contained in the file `ratings.csv`. Each line of this file after the header row represents one rating of one movie by one user, and has the following format:

    userId,movieId,rating,timestamp

------------
### Tags (tags.csv)
All tags are contained in the file `tags.csv`. Each line of this file after the header row represents one tag applied to one movie by one user, and has the following format:

    userId,movieId,tag,timestamp
  
--------------------------
### Movies (movies.csv)
Movie information is contained in the file `movies.csv`. Each line of this file after the header row represents one movie, and has the following format:

    movieId,title,genres

-----------------------------------

### Links (links.csv)

Identifiers that can be used to link to other sources of movie data are contained in the file `links.csv`. Each line of this file after the header row represents one movie, and has the following format:

    movieId,imdbId,tmdbId

Use of the resources listed above is subject to the terms of each provider.

-----------------------------------

**User Ids**

User ids are consistent between `ratings.csv` and `tags.csv` (i.e., the same id refers to the same user across the two files).


**Movie Ids**

Movie ids are consistent between `ratings.csv`, `tags.csv`, `movies.csv`, and `links.csv` (i.e., the same id refers to the same movie across these four data files).


## 🚀 About Me
I'm a beginner developer...

