# FromTheBigScreenToTV
In this project we investigate the question what kind of streaming only movies would do well in terms of revenue with a theatrical release. In general, would it be a good idea for producers or executives of streaming platforms to release some of their movies in the theatres?

This directory holds the following files: 
1. **DimReduction_Visualization** - This file holds the code I created in order to create a visualization using UMAP and HDB Scanner to cluster the vestors that we revied from TF-IDF vectors for each of the description in Netflix Movies. The visualization was created in order to check how well our word2vec model performed by seeing if similar movies were clustered together. Similarity was determiend by both genre and plot of the movie.
2. **Finding Similar Movies TFIDF** - This files holds the code that allowed for our group to find the similar theatrical movies (movies that are not created by a streaming platform) to each Netflix Original Movies based off of the movie description using TD-IDF vectors. We then created a new dataframe with a new column where each netfliz movie was matched to a similar theatrical movie.
3. **K_Means_Clustering** - This file holds the code to perform a KMeans cluster for the movies based off the revenue, genre, runtime and IMDB score in order to determine which attribute led to a higher revenue.
4. **UMAP_Clutering**- This file holds the code to perform a UMAP cluster for the movies based off the revenue, genre, runtime and IMDB score in order to determine which attribute led to a higher revenue.
5. **Revenue** - This fild holds the code to perform EDA analysis to understand feature importance. It also holds the code used to perfrom an ensemble model of Random Forest, XGBoosting, and Neural Networks in order to predict theatrical revenue for Netflix Movies.

Please look at our <a href="https://docs.google.com/presentation/d/1wS6V3FXCwI2EOi0kIK9rb1Nkr7NKHLwixLWhCY4F8mI/edit?usp=sharing"> slides presenation </a> for a summary of our key findings and thought process to approaching the problem. 

CREDIT: The following coding files were authored by Purbasha Majee, Airin Nasyrova, Orlyana Tantchou, and Kimberly Chavez
