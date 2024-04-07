# data-sourcing-challenge

## Background:

The following code prepares data for a recommendation system to help people find movie reviews and related movies.  The data will be extracted from two different sources: The New York Times API and The Movie Database, then merge the data together. The text extracted from these APIs can later be used with natural language processing methods.

The code will require functions, a dotenv file, and api-keys. 
This code is available at Github under (https://github.com/algjor/data-sourcing-challenge/blob/main/retrieve_movie_data.ipynb).

## Description of Code:
This code was completed using the following steps.
(1) - A repository was created called data-sourcing-challenge in Git hub.
(2) - A starter code named retrieve_movie_data.ipynb was created on the local Git repository and pushed to GitHub.
(3) - The dotenv file was created with the nyt_api_key and tmdb_api_key added to be accessed by the code.
(4) - The code has three parts:  
Part 1 - Access the New York Times API.
Part 2 -Access The Movie Database API.
Part 3 - Merge and Clean the Data for Export.
(5) - In Part 1, a query was made to the NYT url and an article searched was performed.  The results from this search were compiled in a list named "reviews_list". The json dumps was used to format the data and a panda dataframe was created.
(6) - In Part 2, a query was made to the Movie database url and movie data was extracted.  The results from this search were stored in a list named "tmdb_movies_list".  The json dumps was used to format the data and a panda dataframe was created.
(7) - In Part 3, the data was merged and cleaned, then exported to a csv file called nyt_tmbd_data.csv.  
(8) - Input from the instructor and learining assistant was used to develop this code.
