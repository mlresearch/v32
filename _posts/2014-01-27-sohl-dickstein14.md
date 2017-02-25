---
pdf: http://proceedings.mlr.press/v32/sohl-dickstein14.pdf
section: cycle-1
title: Hamiltonian Monte Carlo Without Detailed Balance
abstract: We present a method for performing Hamiltonian Monte Carlo that largely
  eliminates sample rejection.  In situations that would normally lead to rejection,
  instead a longer trajectory is computed until a new state is reached that can be
  accepted.  This is achieved using Markov chain transitions that satisfy the fixed
  point equation, but do not satisfy detailed balance.  The resulting algorithm significantly
  suppresses the random walk behavior and wasted function evaluations that are typically
  the consequence of update rejection.  We demonstrate a greater than factor of two
  improvement in mixing time on three test problems.  We release the source code as
  Python and MATLAB packages.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: sohl-dickstein14
month: 0
tex_title: Hamiltonian Monte Carlo Without Detailed Balance
firstpage: 719
lastpage: 726
page: 719-726
sections: 
author:
- given: Jascha
  family: Sohl-Dickstein
- given: Mayur
  family: Mudigonda
- given: Michael
  family: DeWeese
date: 2014-01-27
address: Bejing, China
publisher: PMLR
container-title: Proceedings of the 31st International Conference on Machine Learning
volume: '32'
genre: inproceedings
issued:
  date-parts:
  - 2014
  - 1
  - 27
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
