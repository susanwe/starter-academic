---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Empirical evolution equations
subtitle: ''
summary: ''
authors:
- Susan Wei
- Victor M Panaretos
tags: []
categories: []
date: '2018-02-01'
lastmod: 2020-10-18T16:59:33+03:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-10-18T13:59:33.065033Z'
publication_types:
- '2'
abstract: 'Evolution equations comprise a broad framework for describing
the dynamics of a system in a general state space: when the state
space is finite-dimensional, they give rise to systems of ordinary differential
equations; for infinite-dimensional state spaces, they give rise to partial
differential equations. Several modern statistical and machine learning
methods concern the estimation of objects that can be formalized as solutions
to evolution equations, in some appropriate state space, even if not
stated as such. The corresponding equations, however, are seldom known
exactly, and are empirically derived from data, often by means of nonparametric
estimation. This induces uncertainties on the equations and
their solutions that are challenging to quantify, and moreover the diversity
and the specifics of each particular setting may obscure the path for
a general approach. In this paper, we address the problem of constructing
general yet tractable methods for quantifying such uncertainties, by
means of asymptotic theory combined with bootstrap methodology. We
demonstrates these procedures in important examples including gradient
line estimation, diffusion tensor imaging tractography, and local principal
component analysis. The bootstrap perspective is particularly appealing as
it circumvents the need to simulate from stochastic (partial) differential
equations that depend on (infinite-dimensional) unknowns. We assess the
performance of the bootstrap procedure via simulations and find that it
demonstrates good finite-sample coverage.'
publication: '*Electronic Journal of Statistics*'
---
