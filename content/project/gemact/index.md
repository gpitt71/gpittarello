---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Logo by A.C.
  focal_point: Smart
links:
- icon: 
  icon_pack: fab
  name: Webpage
  url: https://gem-analytics.github.io/gemact/
summary: A comprehensive set of actuarial tools for non-life (re)insurers.
tags:
- reinsurance
- pricing
- collectiveriskmodel
title: GEMAct, an actuarial python package
url_code: "https://github.com/gpitt71/gemact-code"
url_pdf: ""
url_slides: ""
url_video: ""
---
# Introduction

GEMAct is an **actuarial package**, based on the collective risk theory framework, that offers a comprehensive set of tools for **non-life** (re)insurance **pricing**, stochastic **claims reserving**, and **risk aggregation**.

The variety of available functionalities makes GEMAct modeling very flexible and provides actuarial scientists and practitioners with a powerful tool that fits into the expanding community of **Python** programming language.

## Scope

* A collective risk model apparatus to price non-life (re)insurance contracts
* Extend the set of distribution available in scipy to actuarial scientists.
* Tools to estimate the loss reserves. 
* The first Python implementation of the AEP algorithm. 

### Reinsurance treaties


The GEMAct package can be used for pricing the following reinsurance treaties and their combinations.

* Excess-of-Loss (XL).
* Reinstatements.
* Quota-share (QS).
* Deductibles. 
* Stop-loss (SL).

### Computational methods for pricing


The computational methods offered by the GEMAct package for the collective risk model computation are either simulative or non-simulative.

* Recursive method (exact computation).
* Discrete Fourier transform, via the Fast Fourier Transform (FFT) algorithm. 
* Monte Carlo simulation.