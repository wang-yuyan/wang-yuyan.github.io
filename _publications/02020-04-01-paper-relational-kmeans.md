---
title: "Relational Algorithms for k-means Clustering"
alphabetical: true
authors: 'Benjamin Moseley, Kirk Pruhs, Alireza Samadian and Yuyan Wang'
collection: publications
excerpt: 'The majority of learning tasks faced by data scientists involve relational data, yet most standard algorithms for standard learning problems are not designed to accept relational data as input. The standard practice to address this issue is to join the relational data to create the type of geometric input that standard learning algorithms expect. Unfortunately, this standard practice has exponential worst-case time and space complexity. This leads us to consider what we call the Relational Learning Question: ``Which standard learning algorithms can be efficiently implemented on relational data, and for those that can not, is there an alternative algorithm that can be efficiently implemented on relational data and that has similar performance guarantees to the standard algorithm?'' In this paper, we address the relational learning question for two well-known algorithms for the standard k-means clustering problem. We first show that the k-means++ algorithm can be efficiently implemented on relational data. In contrast, we show that the adaptive k-means algorithm likely can not be efficiently implemented on relational data, as this would imply P=#P. However, we show that a slight variation of this adaptive k-means algorithm can be efficiently implemented on relational data, and that this alternative algorithm has the same performance guarantee as the original algorithm, that is that it outputs an O(1)-approximate sketch.'
paperurl: 'https://arxiv.org/abs/2008.00358'

---
