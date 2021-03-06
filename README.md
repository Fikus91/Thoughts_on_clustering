# Thoughts_on_clustering - overview 

This repository contains final project for Data Science bootcamp. Main topic is presentation some methods for clustering mixed data, for this case Titanic dataset was used.

Clustering is a unsupervised method of machine learning, but could be used also in deep learning methodology. Mostly its helpful for data expolartion, and could be treated as prelimitary studies for classification.

This project was prepared as final project for Data Science bootcamp, will be presented some methods of clustering "mixed dataset".

# Goals

The goals was to build and compare some clustering methods:
  - K-Means clustering and MiniBatchKMeans
  - Hierarchical clustering
  - Density based spatial clustering (DBSCAN)
  - Self Organising Map (deep learning method)


# Dependencies

  - Numpy
  - Pandas (03.2020 : for pandas-profiling == 0.25.3)
  - Matplotlib
  - pandas_profiling
  - sklearn
  - yellowbrick
  - scipy
  - minisom
  - pillow
  - glob
  
  
# Roadmap

 1. Data overview 
 2. Preprocessing
 3. K-means clustering
 4. Hierarchical clustering
 5. DBSCAN 
 6. Self Organising Map
 7. Summary

# Final results 

**K-Means**


|    |   cluster_id |   unique_obs |   Survived |     Age |   Siblings/Spouses Aboard |   Parents/Children Aboard |     Fare |   Sex_female |   Sex_male |   Pclass_1 |   Pclass_2 |   Pclass_3 |
|---:|-------------:|-------------:|-----------:|--------:|--------------------------:|--------------------------:|---------:|-------------:|-----------:|-----------:|-----------:|-----------:|
|  0 |            0 |          296 |  -0        | 27.1419 |                  0.530405 |                  0.216216 |  12.2375 |            0 |          1 |         -0 |          0 |          1 |
|  1 |            1 |           94 |   0.968085 | 35.2553 |                  0.553191 |                  0.457447 | 106.126  |            1 |          0 |          1 |          0 |          0 |
|  2 |            2 |           77 |  -0        | 44.2922 |                  0.272727 |                  0.25974  |  62.8949 |           -0 |          1 |          1 |          0 |         -0 |
|  3 |            3 |           72 |  -0        | 23.4028 |                  1.29167  |                  1.09722  |  19.7731 |            1 |          0 |         -0 |          0 |          1 |
|  4 |            4 |           91 |   0        | 33      |                  0.307692 |                  0.142857 |  19.489  |           -0 |          1 |          0 |          1 |          0 |
|  5 |            5 |           72 |   1        | 20.8681 |                  0.5      |                  0.5      |  12.4645 |            1 |          0 |         -0 |          0 |          1 |
|  6 |            6 |           76 |   0.921053 | 28.9803 |                  0.486842 |                  0.605263 |  21.9701 |            1 |          0 |         -0 |          1 |         -0 |
|  7 |            7 |           45 |   1        | 36.7538 |                  0.377778 |                  0.311111 |  74.6373 |           -0 |          1 |          1 |         -0 |         -0 |
|  8 |            8 |           47 |   1        | 22.243  |                  0.340426 |                  0.297872 |  15.5797 |           -0 |          1 |         -0 |         -0 |          1 |
|  9 |            9 |           17 |   1        | 17.0782 |                  0.529412 |                  0.647059 |  21.0951 |           -0 |          1 |          0 |          1 |          0 |


**Hierarchical clustering**

|   cluster_id |   unique_obs |   Survived |   Pclass |   Age |   Siblings/Spouses Aboard |   Parents/Children Aboard |   Fare |   Sex_female |   Sex_male |
|-------------:|-------------:|-----------:|---------:|------:|--------------------------:|--------------------------:|-------:|-------------:|-----------:|
|            1 |           72 |          0 |        3 |    22 |                         1 |                         0 |  7.25  |            0 |          1 |
|            2 |           72 |          1 |        1 |    38 |                         1 |                         0 | 71.283 |            1 |          0 |
|            3 |           94 |          1 |        3 |    26 |                         0 |                         0 |  7.925 |            1 |          0 |
|            4 |           76 |          1 |        1 |    35 |                         1 |                         0 | 53.1   |            1 |          0 |
|            5 |           47 |          0 |        3 |    35 |                         0 |                         0 |  8.05  |            0 |          1 |
|            6 |          296 |          0 |        3 |    27 |                         0 |                         0 |  8.458 |            0 |          1 |
|            7 |           17 |          0 |        1 |    54 |                         0 |                         0 | 51.862 |            0 |          1 |
|            8 |           91 |          0 |        3 |     2 |                         3 |                         1 | 21.075 |            0 |          1 |
|            9 |           77 |          1 |        3 |    27 |                         0 |                         2 | 11.133 |            1 |          0 |
|           10 |           45 |          1 |        2 |    14 |                         1 |                         0 | 30.071 |            1 |          0 |

![**Hierarchical clustering**](https://github.com/Fikus91/Thoughts_on_clustering/blob/master/3.%20Hierarchical_clustering/hierarchy_titanic_normalized.png)


**DBSCAN**






**Self Organising Map**

![***Self Organising Map**](https://github.com/Fikus91/Thoughts_on_clustering/blob/master/4.%20Self%20Organising%20Map/Self%20Organising%20Map%2020.gif)


--in work--
