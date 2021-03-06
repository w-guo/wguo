---
abstract: Topological data analysis (TDA) has emerged as one of the most promising techniques to reconstruct the unknown shapes of high-dimensional spaces from observed data samples. TDA, thus, yields key shape descriptors in the form of persistent topological features that can be used for any supervised or unsupervised learning task, including multi-way classification. Sparse sampling, on the other hand, provides a highly efficient technique to reconstruct signals in the spatial-temporal domain from just a few carefully-chosen samples. Here, we present a new method, referred to as the Sparse-TDA algorithm, that combines favorable aspects of the two techniques. This combination is realized by selecting an optimal set of sparse pixel samples from the persistent features generated by a vector-based TDA algorithm. These sparse samples are selected from a low-rank matrix representation of persistent features using QR pivoting. We show that the Sparse-TDA method demonstrates promising performance on three benchmark problems related to human posture recognition and image texture classification.
authors:
- Wei Guo, Krithika Manohar, Steven L. Brunton and Ashis G. Banerjee
date: "2018-01-08T00:00:00Z"
doi: ""
featured: true
links:
- icon: file-pdf
  icon_pack: fas
  name: pdf
  url: https://ieeexplore.ieee.org/document/8249544
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/w-guo/Sparse-TDA
projects: []
publication: "*IEEE Transactions on Knowledge and Data Engineering, 30*(7): 1403-1408"
publication_short: ""
publication_types: 
- "2"
publishDate: ""
#slides: example
summary: "We present a new method, referred as Sparse-TDA method, that combines persistence image-based TDA method with QR pivoting-based sparse sampling algorithm to transform topological features into image pixels and identify discriminative pixel samples in the presence of noisy and redundant information."
tags:
- Topological data analysis
- Sparse sampling
- Classification
title: "Sparse-TDA: Sparse Realization of Topological Data Analysis for Multi-Way Classification"
url_code: ""
url_pdf: ""
---
<p align="center">
    <img src="Sparse_TDA_pipeline.png" style="width:100%;">
    <em> Pipeline of Sparse-TDA method for multi-way classification</em>
</p>
