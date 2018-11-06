# Music Recommender System using Apache Spark and Python

# Overview

Create a recommender system that will recommend new musical artists to a user based on their listening history. Suggesting different songs or musical artists to a user is important to many music streaming services, such as Pandora and Spotify. In addition, this type of recommender system could also be used as a means of suggesting TV shows or movies to a user (e.g., Netflix).

Spark and the collaborative filtering technique is used for this project.

# Installation

 Python version: 3.6.5 was used for this project

 Libraries used: pyspark

 Jupyter Notebook is required
 

# Datasets

Data is from publicly avaiable song data from audioscrobbler.

The original data files are modified so that the code will run in a reasonable time on a single machine. The reduced data files have been suffixed with _small.txt and contains only the information relevant to the top 50 most prolific users (highest artist play counts).

The original data file user_artist_data.txt contained about 141,000 unique users, and 1.6 million unique artists. About 24.2 million users’ plays of artists are recorded, along with their count.

Note that when plays are scribbled, the client application submits the name of the artist being played. This name could be misspelled or nonstandard, and this may only be detected later. For example, "The Smiths", "Smiths, The", and "the smiths" may appear as distinct artist IDs in the data set, even though they clearly refer to the same artist. So, the data set includes artist_alias.txt, which maps artist IDs that are known misspellings or variants to the canonical ID of that artist.

The artist_data.txt file then provides a map from the canonical artist ID to the name of the artist.
