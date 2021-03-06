# Cryptocurrencies

[Link to Cryptocurrency Code](https://github.com/c-geisel/Cryptocurrencies/blob/main/crypto_clustering.ipynb)

## Purpose
A prominent investment bank is looking to invest in cryptocurrencies. However, it is unknown the best cryptocurrency that would lead to the best investment opportunity. To decide upon the investment avenue, an unsupervised machine learning model is used to observe trends and patterns within the dataset to better make a profitable decision. To accomplish this task the cryptocurrency data is pre-processed, then the features are reduced using a principal component analysis. A K-means machine learning model is then used to cluster components, and visualizations are made to observe trends in the dataset. 

## Results 
Using an elbow curve, the k value is observed to be 4, and thus the dataset is grouped into 4 clusters. The results can be seen in the 3D graph below. 

![3d_plot.png](Resources/3d_plot.png)

The values are then scaled to create a 2d graph to depict the same information.

![2d_plot.png](Resources/2d_plot.png)
