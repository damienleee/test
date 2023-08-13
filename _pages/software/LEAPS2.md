---
title: "Learning based Evolutionary Assistive Paradigm for Surrogate Selection (LEAPS2)"
sitemap: false
permalink: /software/LEAPS2/
author_profile: false
sidebar:
  - title: "LEAPS2"
    image: "/assets/images/LEAPS2_icon.png"
    image_alt: "image"
    text: "Some text here."
    nav: sidebar-sample
toc: true
---

# Introduction  
LEAPS2 (Learning based Evolutionary Assistive Paradigm for Surrogate Selection) [1,2] is a meta-learning framework that recommends three best surrogate models from a pool of 36 surrogate forms for modeling a non-noisy or noisy data set based on some performance metric. The best surrogates are recommended based on LEAPS2's acquired knowledge of surrogate performance for various diverse data sets. For a given data set, LEAPS2 extracts certain data attributes such as dimensionality, nonlinearity, and complexity to estimate performances of different surrogates, and recommends three best surrogates. For noisy data, LEAPS2 uses a user-specified estimate on the limiting value for model goodness-of-fit, beyond which a model can be assumed overfitting (fitting noise / spurious correlations between the inputs and output). This can be specified by either providing a value for minimum RMSE or maximum R2 of a model at the trained points. LEAPS2 compares its estimated performances of surrogates against the limiting value of user-specified goodness-of-fit to determine and reject overfitting surrogates.  

# Download
The desktop application can be downloaded using the following link:

# Web version
The web application can be accessed in the following link:
[https://leaps2.streamlit.app/](https://leaps2.streamlit.app/)  
Please note that the streamlit server is not built for heavy computing! Please download our desktop version for large datasets.

# References
[1] Sushant S. Garud, Iftekhar A. Karimi, Markus Kraft, LEAPS2: Learning based Evolutionary Assistive Paradigm for Surrogate Selection, Computers & Chemical Engineering, Volume 119, 2018, Pages 352-370, ISSN 0098-1354, https://doi.org/10.1016/j.compchemeng.2018.09.008.

[2] Maaz Ahmad, Iftekhar A Karimi, Revised learning based evolutionary assistive paradigm for surrogate selection (LEAPS2v2), Computers & Chemical Engineering, Volume 152, 2021, 107385, ISSN 0098-1354, https://doi.org/10.1016/j.compchemeng.2021.107385.