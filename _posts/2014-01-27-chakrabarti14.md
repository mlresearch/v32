---
title: Joint Inference of Multiple Label Types in Large Networks
abstract: We tackle the problem of inferring node labels in a partially labeled  graph
  where each node in the graph has multiple label types and  each label type has a
  large number of possible labels.  Our primary  example, and the focus of this paper,
  is the joint inference of label  types such as hometown, current city, and employers,
  for users  connected by a social network.  Standard label propagation fails to  consider
  the properties of the label types and the interactions  between them.  Our proposed
  method, called EdgeExplain, explicitly  models these, while still enabling scalable
  inference under a  distributed message-passing architecture.  On a billion-node
  subset of the Facebook social network,  EdgeExplain significantly outperforms label
  propagation for several  label types, with lifts of up to 120% for recall@1 and
  60% for  recall@3.
section: cycle-2
layout: inproceedings
id: chakrabarti14
month: 0
firstpage: 874
lastpage: 882
page: 874-882
sections: 
author:
- given: Deepayan
  family: Chakrabarti
- given: Stanislav
  family: Funiak
- given: Jonathan
  family: Chang
- given: Sofus
  family: Macskassy
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
pdf: http://proceedings.mlr.press/v32/chakrabarti14/chakrabarti14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
