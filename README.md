This project prepares data for a recommendation system to help people find movie reviews and the related movies. The process implemented in this project occurs as follows
1) Data is first extracted from the New York Times API: The application calls the New York times articles search API and retrieves movies reviewed between January 1st 2013 and May 31st 2023.
2) The Applicaiton then retrieves the Movie titles retrieved from New York Times API.
3) The application then calls the The Movie Database API's to retrieve the movie id and the movie details for each Movie Title retrieved from the New York Times API.
4) The Application then saves all the relevant movie details to a dictionary which is later converted to a dataframe
5) The Application then merges the data retrieved from the New York Times API and the Movie Database API's, based on a movie title. It then cleans up the data.
6) The applicaiton then creates an output file for the data

The code in this project is written in Python using the Pandas library. It uses several Pandas functions such as concat, join, groupby, sort etc and also uses DataFrames and Pivot tables.

The project can be run on either Visual Studio Code or Jupyter.
