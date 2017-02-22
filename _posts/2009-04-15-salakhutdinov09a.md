---
title: Deep Boltzmann Machines
abstract: We present a new learning algorithm for Boltzmann machines that contain
  many layers of hidden variables. Data-dependent expectations are estimated using
  a variational approximation that tends to focus on a single mode, and data-independent
  expectations are approximated using persistent Markov chains. The use of two quite
  different techniques for estimating the two types of expectation that enter into
  the gradient of the log-likelihood makes it practical to learn Boltzmann machines
  with multiple hidden layers and millions of parameters. The learning can be made
  more efficient by using a layer-by-layer ``pre-training'' phase that allows variational
  inference to be initialized by a single bottom-up pass. We present results on the
  MNIST and NORB datasets showing that deep Boltzmann machines learn good generative
  models and perform well on handwritten digit and visual object recognition tasks.
pdf: "./salakhutdinov09a/salakhutdinov09a.pdf"
layout: inproceedings
key: salakhutdinov09a
month: 0
firstpage: 448
lastpage: 455
origpdf: http://jmlr.org/proceedings/papers/v5/salakhutdinov09a/salakhutdinov09a.pdf
sections: 
authors:
- given: Ruslan
  family: Salakhutdinov
- given: Geoffrey
  family: Hinton
---
