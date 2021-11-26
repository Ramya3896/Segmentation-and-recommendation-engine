# Segmentation-and-recommendation-engine
Let us segment the customers based on a wine data and build a recommendation system using classification model to recommend the new wine

## About Dataset
The wine data set consists of the 14 clomuns and 178 rows.

The features are: Alcohol content, Malic_Acid, Ash, Ash_Alcanity, Magnesium, Total_Phenols, Flavanoids, Nonflavanoid_Phenols, Proanthocyanins, Color_Intensity, Hue, OD280, Proline , and Customer_Segment 

 The last column in true label of the segment to which the customer belong to. 
 
 Our first goal is to train KMeans Clustering algorithm to segment the customers and compare it with true label.
 
 
## Segmentation
From the elbow method, the optimal number of clusters is found to be 3.
Elbow method:

![download](https://user-images.githubusercontent.com/45202209/143525307-79d28f8e-771e-4764-8171-5ae1ebdd8f70.png)

#### The number of clusters in the given dataset is also 3. Thus we can say that algorithm has performed well in identifying the number of clusters.

# Recommendation System

Here the objective is to reduce the dimensionality of the data and predict to which segment the new type of wine can be recommended.

Using frist 2 principle components, we can predict the segments of customers with great accuracy  using Logistic model.
