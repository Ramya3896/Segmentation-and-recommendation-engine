# Segmentation-and-recommendation-engine
Let us segment the customers based on a wine data and build a recommendation system using classification model to recommend the new wine

## About Dataset
The wine data set consists of the 14 clomuns and 178 rows.
The information about features is as follows:
#   Column                Non-Null Count  Dtype  
---  ------                --------------  -----  
 0   Alcohol               178 non-null    float64
 1   Malic_Acid            178 non-null    float64
 2   Ash                   178 non-null    float64
 3   Ash_Alcanity          178 non-null    float64
 4   Magnesium             178 non-null    int64  
 5   Total_Phenols         178 non-null    float64
 6   Flavanoids            178 non-null    float64
 7   Nonflavanoid_Phenols  178 non-null    float64
 8   Proanthocyanins       178 non-null    float64
 9   Color_Intensity       178 non-null    float64
 10  Hue                   178 non-null    float64
 11  OD280                 178 non-null    float64
 12  Proline               178 non-null    int64  
 13  Customer_Segment      178 non-null    int64  
 
 The last column in true label of the segment to which the customer belong to. 
 
 Our first goal is to train KMeans Clustering algorithm to segment the customers and compare it with true label.
 
 
## Segmentation
From the elbow method, the optimal number of clusters is found to be 3.
![download](https://user-images.githubusercontent.com/45202209/143525307-79d28f8e-771e-4764-8171-5ae1ebdd8f70.png)

#The number of clusters in the given dataset is also 3. Thus algorithm has performed well in identifying the number of clusters.

