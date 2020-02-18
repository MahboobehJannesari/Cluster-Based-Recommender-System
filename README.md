# Cluster Based Rrecommender System
## Objective: Which Hotel to recommend?
In this work, I create a recommendation system that ask customers about some their options, then suggest them best one. My goal for this project is to accurately match customers with hotel inventory in highly competitive market.

I would recommend hotels with the largest similarity to the user request. This recommender system is highly dependent on defining an appropriate similarity measure. Eventually, I select a subset of hotels to for training  and to determine an order in which to display the hotels.

This hotel recommender engine is a model-based Content-Based(CB) recommendation system. In other words, I extracted some information from the dataset, and use that as a “model” to make recommendations without having to use the complete dataset every time. This approach offers the benefits of both speed and scalability.

After some preprocessing and feature engineering, I used Kmeans method to cluster information of 10 hotels for one year. Then, for all, I predict the cluster for all hotels in Berlin.

For recommendation, after gathering information from user, the most similar cluster will be offered. Hotels in suggestion will be sorted by the maximum similarity to the user request.
