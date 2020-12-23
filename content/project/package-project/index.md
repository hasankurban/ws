---
date: "2020-04-20T00:00:00Z"
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

summary: Data Clustering with EM (DCEM) for Big Data, an R package
tags:
- Unsupervised Learning
- Clustering
- Big Data
- Expectation Maximization
- Data Mining
- Heap
- R programming
title: R Package 
url_code: ""
url_pdf: "https://cran.r-project.org/web/packages/DCEM/DCEM.pdf"
url_slides: ""
url_video: ""
---

In this paper we introduced the DCEM package for clustering big data. DCEM is developed using R and is publically accessible on the Comprehensive R Archive Network (CRAN) at https://CRAN.R-project.org/. In particular we demonstrated that significant improvements in run time and number of iterations are achieved by embedding a heap structure within the framework of the traditional expectation maximisation algorithm Dempster et al. (1977). Our package makes use of the proposed data driven approach Kurban, Jenne, and Dalkilic (2016b) that, (1) avoids visiting all data and, (2) avoid continually re-visiting the data, to speed up the convergence process. We illustrated the practical utility of DCEM by performing several experiments across application domains that highlight the significant improvement in performance. In future, we would like to 1) extend this approach to use data structures that enforce total ordering for example, kd-tree. Min heap is a partially ordered structure and hence does not enforece a strict oredering on the data. We argue that by using a totally ordered structure, we can further improve the performance of iterative learning algorithms, 2) use this approach in contemporary iterative data mining algorithms i.e., k-means, an example of such work is also discussed in Kurban and Dalkilic (2017).