---
pdf: http://proceedings.mlr.press/v32/shrivastava14/shrivastava14.pdf
section: cycle-1
title: Densifying One Permutation Hashing via Rotation for Fast Near Neighbor Search
abstract: The query complexity of \em locality sensitive hashing (LSH) based similarity
  search is dominated by the number of hash evaluations, and this number grows with
  the data size \citeProc:Indyk_STOC98. In industrial applications such as search
  where the data are often high-dimensional and binary (e.g., text n-grams),  \em
  minwise hashing is widely adopted, which requires applying a large number  of permutations
  on the data. This is  costly in computation and energy-consumption.    In this paper,
  we propose a  hashing technique which generates all the necessary hash evaluations
  needed for similarity search, using  one single permutation.  The heart of the proposed
  hash function is a  “rotation” scheme which densifies the sparse sketches of \em
  one permutation hashing \citeProc:Li_Owen_Zhang_NIPS12 in an unbiased fashion thereby
  maintaining the LSH property. This makes the obtained sketches suitable for hash
  table construction. This idea of rotation presented in this paper could be of independent  interest  for
  densifying  other types of sparse sketches.     Using our proposed hashing method,
  the  query time of a (K,L)-parameterized LSH is reduced from  the typical O(dKL)
  complexity to merely O(KL+dL), where d is the  number of nonzeros of the data vector,
  K is the number of hashes in each hash table, and L is the number of hash tables.  Our
  experimental evaluation on real data confirms that the proposed scheme significantly
  reduces the query processing time over minwise hashing without loss in retrieval
  accuracies.
layout: inproceedings
id: shrivastava14
month: 0
firstpage: 557
lastpage: 565
page: 557-565
sections: 
author:
- given: Anshumali
  family: Shrivastava
- given: Ping
  family: Li
date: 2014-01-27
address: Bejing, China
publisher: PMLR
container-title: Proceedings of The 31st International Conference on Machine Learning
volume: '32'
genre: inproceedings
issued:
  date-parts:
  - 2014
  - 1
  - 27
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
