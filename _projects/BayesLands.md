---
layout: project
title: 'BayesLands'
caption: "BayesLands: Bayesian inference via Parallel Tempering for Badlands"
description: >
  Bayesian inference via Parallel Tempering for Badlands
date: '01-01-2019'
image: /assets/img/projects/bl_cm_likl_contour.png
links:
  - title: BayesLands GitHub page
    url: https://github.com/intelligentEarth/pt-Bayeslands
sitemap: false
---
Bayesian inference via Parallel Tempering for  Badlands
=====


## Overview

**Ba**sin an**d** **Lan**dscape **D**ynamic**s** (**Badlands**) is a parallel TIN-based landscape evolution model, built to simulate topography development at various space and time scales. The model is capable of simulating hillslope processes (**linear** & **non-linear** diffusion), fluvial incision (*'modified'* **Stream Power Law**, **Transport Capacity Law** both for sediment  erosion/transport/deposition), spatially and temporally varying geodynamic (horizontal + vertical displacements) and climatic forces which can be used to simulate changes in base level, as well as effects of climate changes or sea-level fluctuations. The model uses  [**gFlex**](https://github.com/awickert/gFlex) package which is designed to solve elastic plate flexure for applications to Earth's lithosphere.

![Rain Posterior Plot](/assets/img/projects/bl_rain_posterior.png)
![Rain Trace Plot](/assets/img/projects/bl_rain_trace.png)
![Crater Two parameter posterior](/assets/img/projects/bl_crater50k_twoparam.png)
![Crater Two parameter trace](/assets/img/projects/bl_crater50k_twoparam_trace.png)

Comparison of PT-Bayeslands with SC-Bayeslands for the Cr problem for 50,000 iterations. The panels show  estimates of the posterior distribution and trace-plot of the precipitation ($\rho$) for the SC-Bayeslands and PT-Bayeslands respectively. \textcolor{blue}{The trace-plots show the accepted or current values of the chain for the  given samples}. Note that the results for SC-Bayeslands are taken from earlier single chain experiments (with 5 \% burnin) while PT-Bayeslands features 25 \%burn-in.


<!-- **hy-drawer** is a touch-enabled drawer component for the modern web. It focuses on providing a fun, natural feel in both the Android and iOS stock browser, while being performant and easy to use. It is the perfect companion for mobile-first web pages and progressive web apps.

> A touch-enabled drawer component for the modern web.
{:.lead}

**hy-drawer** is used by hundreds of sites as part of the [Hydejack] Jekyll theme.

[hydejack]: ../README.md -->
