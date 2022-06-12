---
date: "2022-06-10T00:00:00Z"
external_link: ""
image:
  caption: 
  focal_point: 
#links:
#- icon: 
#  icon_pack: 
#  name: 
#  url: 
#slides: 


summary:  A paired index structure for k-Nearest
Neighbor Search Algorithms over High Dimensional Data & Large Data Sets (k-NN-p)
tags:
- B+ Trees
- High Dimensional Data 
- Paired Indexing
- Big Data Mining
- Nearest Neighbors

title: A paired index structure for k-Nearest Neighbor Search Algorithms
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
Existing k-Nearest-Neighbors algorithms become
overwhelmed when presented with large data. While space partitioning data structures such as k-d tree and ball-tree improve the performance in a larger data set, they suffer when the data is high dimensional. We observe that space partitioning becomes ineffective in high-dimensional spaces and explores most of the
search space to find the nearest neighbors. Our strategy is to partition the data into small clusters of points that are similarly distanced from a reference point in a B+tree data structure that is easy to parallelize and in a way that narrows down the search of k-Nearest-Neighbors for a query to a few clusters.
Further, we establish that any indexing applicable to the entire data set can be extended to each cluster, enabling even faster query time at the node level. We then present our algorithm and its theoretical complexities and show that our approach outperforms the naive, k-d tree, ball-tree based k-NN and MRPT index-based approximate k-NN search in high dimensional data.
Finally, we conclude with experimental results that illustrate the
performance improvements outlined in our approach.