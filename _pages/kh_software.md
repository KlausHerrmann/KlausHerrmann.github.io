---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## multIntTestFunc
**multIntTestFunc** is a **R** package that implements test functions for multivariate numerical integration routines.
This allows to test, verify and compare implementations of different algorithms.
The implementation in the package allows for example to loop over the available test functions, allowing to automate tests and comparisons.
In order to be widely applicable, the package covers six different integration domains (unit hypercube, unit ball, unit sphere, standard simplex, non-negative real numbers and R^n).
For each domain several functions with different properties (smooth, non-differentiable, ...) are available. The functions are available in all dimensions n >= 1.

The stable version is available on CRAN: <a href="https://CRAN.R-project.org/package=multIntTestFunc">CRAN multIntTestFunc</a>.
The current version and documentation can be found on GitHub: <a href="https://github.com/KlausHerrmann/multIntTestFunc">GitHub multIntTestFunc</a>.


