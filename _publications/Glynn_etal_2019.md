---
title: "Bayesian Analysis of Dynamic Linear Topic Models"
collection: publications
permalink: /publication/DLTM
date: 2019-03-01
venue: 'Bayesian Analysis'
paperurl: https://g-lynn.github.io/files/GlynnTokdarHowardBanks_2019.pdf
doi: 10.1214/18-BA1100
pubtype: 'journal'
authors: 'Glynn, C., Tokdar, S. T., Howard, B., and Banks, D. L.'
excerpt_separator: ""
---

[Download paper here](https://g-lynn.github.io/files/GlynnTokdarHowardBanks_2019.pdf)

[Software and Data](https://github.com/G-Lynn/DLTM)

[General audience article and interactive visualizations](http://g-lynn.github.io/DLTM/)

Discovering temporal evolution of themes from a time-stamped collection of text poses a challenging statistical learning problem. Dynamic topic models offer a probabilistic modeling framework to decompose a corpus of text documents into “topics”, i.e., probability distributions over vocabulary terms, while simultane- ously learning the temporal dynamics of the relative prevalence of these topics. We extend the dynamic topic model of Blei and Lafferty (2006) by fusing its multinomial factor model on topics with dynamic linear models that account for time trends and seasonality in topic prevalence. A Markov chain Monte Carlo (MCMC) algorithm that utilizes Po ́lya-Gamma data augmentation is developed for posterior sampling. Conditional independencies in the model and sampling are made explicit, and our MCMC algorithm is parallelized where possible to allow for inference in large corpora. Our model and inference algorithm are validated with multiple synthetic examples, and we consider the applied problem of model- ing trends in real estate listings from the housing website Zillow. We demonstrate in synthetic examples that sharing information across documents is critical for accurately estimating document-specific topic proportions. Analysis of the Zillow corpus demonstrates that the method is able to learn seasonal patterns and locally linear trends in topic prevalence.
