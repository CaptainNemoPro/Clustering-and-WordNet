# Clustering and WordNet

# Introduction

![alt text](https://th.bing.com/th/id/R.a1293480c0ed6bf1ff72d05fe29192f7?rik=DVw9%2bCEtr%2bP0zw&riu=http%3a%2f%2fgifimage.net%2fwp-content%2fuploads%2f2017%2f11%2fintroduction-gif-7.gif&ehk=fIq34BcPvQ7sY2qaVQQHd8qRyH%2bQc7gVgyBiq9zbFx4%3d&risl=&pid=ImgRaw&r=0)

Clustering involves grouping similar data points together in a given dataset. This is typically done to gain a better understanding of the data. The ideal number of clusters can be determined by creating an elbow plot, which identifies the point where the inertia begins to decrease at a negligible rate.

For this particular task, K-means clustering was utilized.

# Steps

1. The data was cleaned.
2. The data was converted into numerical format by vectorizing it.
3. Clusters were created using K-means clustering algorithm by inputting the vectorized data into the model.
4. Made word clouds

# Words clouds

![alt text](https://i.ytimg.com/vi/-2gH7Xfn0AI/maxresdefault.jpg)

I partitioned the data into clusters and generated a word cloud for each one. The purpose was to evaluate the clustering's effectiveness by assessing if the words in each word cloud cohere into a specific theme. If this is the case for all the word clouds, we can conclude that the clusters are of good quality and meaningful.
