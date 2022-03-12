---
title: "MIA"
excerpt: "A multi-view item side information enhanced recommendation algorithm<br/><img src='/images/mia.svg' width='500'>"
collection: portfolio
date: 2021-12-01
---
**MIA** is a side information-enhanced recommender system named after its most innovative component, the Mutual Information-based Alignment metric, as shown in the system architecture. It is designed to better digest side information provided to a recommender system along with the user interaction history. 

![The overall architecture of MIA](/images/mia.svg)

A thorough comparison to a broad selection of baselines and a careful complexity and convergence rate analysis on MIA and the best performing baseline, KGAT, have shown that MIA is able to achieve state-of-the-art performance with a notable speed improvement. 


![Convergence speed comparison between MIA and KGAT on four evaluation
datasets wrt Recall@20](/images/mia_vs_kgat.png)

More details about the algorithm and experiment results can be found in the [full paper](http://veecg.github.io/files/vivian_ece_thesis.pdf).


