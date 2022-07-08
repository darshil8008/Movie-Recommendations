# Movie-Recommendations
This example demonstrates Collaborative filtering using the Movielens dataset to recommend movies to users.  

Downloaded the actual data from http://files.grouplens.org/datasets/movielens/ml-latest-small.zip" and will use the ratings.csv file.  

The model computes a match score between user and movie embeddings via a dot product, and adds a per-movie and per-user bias. 

The match score is scaled to the [0, 1] interval via a sigmoid function. 
