# Clustering the Accessories Dataset

## Executive Summary:

Tous Jewelry store is an inexpensive brand that sells a variety of items including rings, earrings, pendants. Items can be made of different materials including gold, silver, and titanium, as well as a variety of gymstones and crystals. In this case study, we would like to cluster the accessories dataset and find out the underlying pattern of the data. The data wa obtained via web scraping the official Tous website, and is available on Kaggle on the following link https://www.kaggle.com/arimaha/what-makes-a-best-seller-item. We used Hierarchical Clustering and obtained a Silhouette score of approximately 0.74.

#### Research Question:

We would like to know whether clustering the dataset would cluster them based on the item type. Therefore, we removed the columns corresponding to the item type before applying the clustering model, then we checked our clusters against the initial item types.

#### Findings:

The resulting clusters did not match the item types. Rather, the clusters demonstrated the different price ranges of the items. Moreover, one of the clusters detected outliers among the price feature.

#### Future Work:

Further research could be done exploring different clustring models. Also, we could try to remove the price since it is a strong feature, and check whether our model clusters the data differently making more use of the other features.

