---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---

* __BCEA__     [![GitHub](../images/mark-github.svg)](https://github.com/n8thangreen/BCEA), [CRAN](https://cran.r-project.org/web/packages/BCEA/index.html)
  * Bayesian Cost Effectiveness Analysis. Given the results of a Bayesian model (possibly based on MCMC) in the form of simulations from the posterior distributions of suitable variables of costs and clinical benefits for two or more interventions, produces a health economic evaluation. Compares one of the interventions (the "reference") to the others ("comparators"). Produces many summary and plots to analyse the results.    

* __blendR__    [![GitHub](../images/mark-github.svg)](https://github.com/StatisticsHealthEconomics/blendR) [CRAN](https://cran.r-project.org/web/packages/blendR/index.html)
  * Create a blended curve from two survival curves, which is particularly useful
          for survival extrapolation in health technology assessment. The main idea is to
          mix a flexible model that fits the observed data well with a parametric model that
          encodes assumptions about long-term survival. The two curves are blended into a
          single survival curve that is identical to the first model over the range of 
          observed times and gradually approaches the parametric model over the extrapolation
          period based on a given weight function. This approach allows for the inclusion of
          external information, such as data from registries or expert opinion, to guide
          long-term extrapolations, especially when dealing with immature trial data.
          See Che et al. (2022) <doi:10.1177/0272989X221134545>.

* __outstandR__    [![GitHub](../images/mark-github.svg)](https://github.com/StatisticsHealthEconomics/outstandR), [CRAN](https://cran.r-project.org/web/packages/outstandR/index.html)
  * An R package for model-based standardisation for indirect treatment comparison (ITC).   

* __CEdecisiontree__    [![GitHub](../images/mark-github.svg)](https://github.com/Health-Economics-in-R/CEdecisiontree)
  * Lightweight cost-effectiveness analysis using decision trees.    

* __NMA__    [![GitHub](../images/mark-github.svg)](https://github.com/ICON-in-R/NMA)
  * Minimal network meta-analysis with BUGS from R.    



