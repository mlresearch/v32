---
title: Fast large-scale optimization by unifying stochastic gradient and quasi-Newton
  methods
abstract: We present an algorithm for minimizing a sum of functions that combines
  the computational efficiency of stochastic gradient descent (SGD) with the second
  order curvature information leveraged by quasi-Newton methods. We unify these disparate
  approaches by maintaining an independent Hessian approximation for each contributing
  function in the sum. We maintain computational tractability and limit memory requirements
  even for high dimensional optimization problems by storing and manipulating these
  quadratic approximations in a shared, time evolving, low dimensional subspace. This
  algorithm contrasts with earlier stochastic second order techniques that treat the
  Hessian of each contributing function as a noisy approximation to the full Hessian,
  rather than as a target for direct estimation. Each update step requires only a
  single contributing function or minibatch evaluation (as in SGD), and each step
  is scaled using an approximate inverse Hessian and little to no adjustment of hyperparameters
  is required (as is typical for quasi-Newton methods). We experimentally demonstrate
  improved convergence on seven diverse optimization problems. The algorithm is released
  as open source Python and MATLAB packages.
section: cycle-2
layout: inproceedings
series: Proceedings of Machine Learning Research
id: sohl-dicksteinb14
month: 0
tex_title: Fast large-scale optimization by unifying stochastic gradient and quasi-Newton
  methods
firstpage: 604
lastpage: 612
page: 604-612
order: 604
cycles: false
author:
- given: Jascha
  family: Sohl-Dickstein
- given: Ben
  family: Poole
- given: Surya
  family: Ganguli
date: 2014-06-18
number: 2
address: Bejing, China
publisher: PMLR
container-title: Proceedings of the 31st International Conference on Machine Learning
volume: '32'
genre: inproceedings
issued:
  date-parts:
  - 2014
  - 6
  - 18
pdf: http://proceedings.mlr.press/v32/sohl-dicksteinb14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
