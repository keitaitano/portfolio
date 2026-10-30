---
title: "Uncertainty evaluation and calibration of neural network regression for melt viscosity"
authors:
- Yayako Aneishi
- Toru Sugawara
- Kenta Ueki
- me
date: "2026-07-09T00:00:00Z"

# 目次（On this page）を非表示
toc: false

# 論文の掲載情報
publication_types: ["article-journal"]
publication: "*Journal of Non-Crystalline Solids*, 690, 124270 (2026)"
publication_short: "*J. Non-Cryst. Solids*"

peer_reviewed: true
open_access: false

abstract: "Machine learning models like neural networks are great at predicting the viscosity of molten glass, but it is often hard to know how much we can trust their individual predictions. In this study, we evaluate Monte Carlo dropout for estimating predictive uncertainty and show that standard settings often overestimate error margins. By applying a straightforward calibration method, we make the model's confidence estimates much more realistic and reliable for glass science applications."

tags:
- Machine Learning
- Material Science

featured: false

# 外部リンクボタン
links:
- name: DOI
  url: https://doi.org/10.1016/j.jnoncrysol.2026.124270
- name: Publisher Page
  url: https://www.sciencedirect.com/science/article/abs/pii/S0022309326003297
---

### Key Highlights
- **Reliability of Prediction Models:** Evaluates how well neural networks can quantify their own predictive uncertainty when estimating the viscosity of molten glass.
- **Uncertainty Calibration:** Shows that commonly used uncertainty estimation techniques (MC dropout) tend to overestimate errors, and introduces an effective calibration method to produce realistic, dependable confidence bounds.