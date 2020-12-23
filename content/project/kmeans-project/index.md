---
date: "2017-12-11T00:00:00Z"
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


summary: A Novel Approach to Optimization of Iterative Machine Learning Algorithms 
tags:
- Clustering
- Big Data
- Machine Learning
- Data Mining
- Heap
title: Iterative Machine Learning 
url_code: ""
url_pdf: "https://ieeexplore.ieee.org/abstract/document/8257917"
url_slides: ""
url_video: ""
---

In this work, we have described an optimization approach that can be used over any iterative optimization
algorithms to improve their training run-time complexity. To the best of our knowledge, this is the first work that theoretically shows convergence of iterative algorithms over heap structure–instead of over a cost function. This approach is tested over k-means (KM) and expectation-maximization algorithm (EM-T). The experimental results show dramatic improvements over KM and EM-T training run-time through different kinds of testing: scale, dimension, and separability. Regarding cluster error, the traditional algorithms’ and our
extended algorithms’ performances are similar. For future work, clearly one obvious step is to add seeding to KM* drawing from both k-means++ and kd trees. Additionally,we are interested in the broader question of this approach to iterative converging algorithms. Further, are there better structures than heaps? Lastly, parallelization offers some new challenges, but also opportunities.
