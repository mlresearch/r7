---
abstract: The fastest known exact algorithms for scorebased structure discovery in
  Bayesian networks on n nodes run in time and space 2nnO(1). The usage of these algorithms
  is limited to networks on at most around 25 nodes mainly due to the space requirement.
  Here, we study space-time tradeoffs for finding an optimal network structure. When
  little space is available, we apply the Gurevich-Shelah recurrence-originally proposed
  for the Hamiltonian path problem-and obtain time 22n-snO(1) in space 2snO(1) for
  any s = n/2, n/4, n/8, . . .; we assume the indegree of each node is bounded by
  a constant. For the more practical setting with moderate amounts of space, we present
  a novel scheme. It yields running time 2n(3/2)pnO(1) in space 2n(3/4)pnO(1) for
  any p = 0, 1, . . ., n/2; these bounds hold as long as the indegrees are at most
  0.238n. Furthermore, the latter scheme allows easy and efficient parallelization
  beyond previous algorithms. We also explore empirically the potential of the presented
  techniques.
title: Exact Structure Discovery in Bayesian Networks with Less Space
year: '2009'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: parviainen09a
month: 0
tex_title: Exact Structure Discovery in {B}ayesian Networks with Less Space
firstpage: 444
lastpage: 451
page: 444-451
order: 444
cycles: false
bibtex_author: Parviainen, Pekka and Koivisto, Mikko
author:
- given: Pekka
  family: Parviainen
- given: Mikko
  family: Koivisto
date: 2009-06-18
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 25th Conference on Uncertainty in Artificial Intelligence
volume: R7
genre: inproceedings
issued:
  date-parts:
  - 2009
  - 6
  - 18
pdf: https://raw.githubusercontent.com/mlresearch/r7/main/assets/parviainen09a/parviainen09a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
