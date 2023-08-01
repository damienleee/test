---
title: "Learning based Evolutionary Assistive Paradigm for Surrogate Selection (LEAPS2)"
sitemap: false
permalink: /software/LEAPS2/
author_profile: false
sidebar:
  - title: "LEAPS2"
    image: "/assets/images/avatar-icon.png"
    image_alt: "image"
    text: "Some text here."
    nav: sidebar-sample
toc: true
---

# Introduction  
LEAPS2 (Learning based Evolutionary Assistive Paradigm for Surrogate Selection) [1,2] is a meta-learning framework that recommends three best surrogate models from a pool of 36 surrogate forms for modeling a non-noisy or noisy data set based on some performance metric. The best surrogates are recommended based on LEAPS2's acquired knowledge of surrogate performance for various diverse data sets. For a given data set, LEAPS2 extracts certain data attributes such as dimensionality, nonlinearity, and complexity to estimate performances of different surrogates, and recommends three best surrogates. For noisy data, LEAPS2 uses a user-specified estimate on the limiting value for model goodness-of-fit, beyond which a model can be assumed overfitting (fitting noise / spurious correlations between the inputs and output). This can be specified by either providing a value for minimum RMSE or maximum R2 of a model at the trained points. LEAPS2 compares its estimated performances of surrogates against the limiting value of user-specified goodness-of-fit to determine and reject overfitting surrogates.  

# Download