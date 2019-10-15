---
title: "Analyzing second order stochasticity of neural spiking under stimuli-bundle exposure"
collection: publications
permalink: /publication/DAPP
date: 2019-10-01
venue: '<b><i>(Invited revision)</i></b>'
paperurl: 'https://g-lynn.github.io/files/GlynnTokdar_etal_2019+.pdf'
doi: 
pubtype: 'submitted'
authors: 'Glynn, C., Tokdar, S. T., Zaman, A., Caruso, V., Mohl, J. T., Willett, S., M., and Groh, J. M.'
excerpt_separator: ""
---

[Download paper here](https://g-lynn.github.io/files/GlynnTokdar_etal_2019+.pdf)

[Sofware and Data](https://github.com/G-Lynn/DPMMM)

Conventional analysis of neuroscience data involves computing average neural ac- tivity over a group of trials and/or a period of time. This approach may be particularly problematic when assessing the response patterns of neurons to more than one simultaneously presented stimulus. In such cases, the brain must represent each individual component of the stimuli bundle, but trial-and-time-pooled averaging methods are fundamentally unequipped to address the means by which multi-item representation occurs. We introduce and investigate a novel statistical analysis framework that relates the firing pattern of a single cell, exposed to a stimuli bundle, to the ensemble of its firing patterns under each constituent stimulus. Existing statistical tools focus on what may be called “first order stochasticity” in trial-to-trial variation in the form of unstructured noise around a fixed firing rate curve associated with a given stimulus. Our analysis is based upon the theoretical premise that exposure to a stimuli bundle induces additional stochasticity in the cell’s response pattern, in the form of a stochastically varying recombination of its single stimulus firing rate curves. We discuss challenges to statistical estimation of such “second order stochasticity” and address them with a novel dynamic admixture Poisson process (DAPP) model. DAPP is a hierarchical point process model that decomposes second order stochasticity into a Gaussian stochastic process and a random vector of interpretable features, and, facilitates borrowing of information on the latter across repeated trials through latent clustering. We present empirical evidence of the utility of the DAPP analysis with synthetic and real neural recordings.
