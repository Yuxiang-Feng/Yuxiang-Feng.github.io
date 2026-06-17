---
title:          "Ill-Conditioning in Dictionary-Based Dynamic-Equation Learning: A Systems Biology Case Study"
date:           2026-03-11 
selected:       true
#pub:            "International Conference on Machine Learning (ICML)"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
#pub_date:       "2024"
semantic_scholar_id: 0348ad9356559a54ab3ed781b43c3e375c85a298  # use this to retrieve citation count
abstract: >-
  Data-driven discovery of governing equations from time-series data provides a powerful framework for understanding complex biological systems. Library-based approaches that use sparse regression over candidate functions have shown considerable promise, but they face a critical challenge when candidate functions become strongly correlated: numerical ill-conditioning. Poor or restricted sampling, together with particular choices of candidate libraries, can produce strong multicollinearity and numerical instability. In such cases, measurement noise may lead to widely different recovered models, obscuring the true underlying dynamics and hindering accurate system identification. Although sparse regularization promotes parsimonious solutions and can partially mitigate conditioning issues, strong correlations may persist, regularization may bias the recovered models, and the regression problem may remain highly sensitive to small perturbations in the data. We present a systematic analysis of how ill-conditioning affects sparse identification of biological dynamics using benchmark models from systems biology. We show that combinations involving as few as two or three terms can already exhibit strong multicollinearity and extremely large condition numbers. We further show that orthogonal polynomial bases do not consistently resolve ill-conditioning and can perform worse than monomial libraries when the data distribution deviates from the weight function associated with the orthogonal basis. Finally, we demonstrate that when data are sampled from distributions aligned with the appropriate weight functions corresponding to the orthogonal basis, numerical conditioning improves, and orthogonal polynomial bases can yield improved model recovery accuracy across two baseline models.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Yuxiang Feng
  - Niall M Mangan
  - Manu Jayadharan
links:
  Paper: https://arxiv.org/abs/2603.11330
  Code: https://github.com/mjayadharan/IllposedLearning
  #Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
