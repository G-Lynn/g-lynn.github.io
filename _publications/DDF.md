---
title: "Sequential Demand Forecasting of Bursty Count Data"
collection: publications
permalink: /publication/DDF
date: 2019-04-01
venue: '<b><i>(Submitted for review)</i></b>'
paperurl: 'https://g-lynn.github.io/files/IrieGlynnAktekin_2019+.pdf'
doi: 
pubtype: 'submitted'
authors: 'Irie, K., Glynn, C., and Aktekin, T.'
excerpt_separator: ""
---

[Download paper here](https://g-lynn.github.io/files/IrieGlynnAktekin_2019+.pdf)

Existing methods for sequentially analyzing count data typically utilize a discounting strategy, where the contribution of past observations to parameter updates diminishes with elapsed time. Discount factor techniques offer an intuitive approach to sequentially updating parameters with weighted contributions from all previously observed data; however, when the time series undergoes a sudden change and the observed count significantly jumps, parameter estimates are slow to adapt, as they are heavily informed by data observed prior to the structural break. Immediately following such bursts, predictive performance degrades. In this study, we introduce an augmented Poisson-gamma state-space (PGSS) model whose state evolution structure is flexible and responsive to sudden changes in the level of counts, focusing on consumer demand settings where sequential and online learning/forecasting are of great interest. Such adaptability is achieved by augmenting the state vector of the PGSS model with an additional state variable for a time-varying discount factor. We develop an efficient particle-based estimation procedure that is suitable for sequential analysis, allowing us to esti- mate dynamic state variables and static parameters via closed form conditional sufficient statistics. To illustrate how the state-augmented PGSS model performs with data that exhibit bursts, we present results from a simulation study and two case studies to monitor and forecast web traffic and ridesharing demand. We show that – in the presence of structural breaks – our proposed approach yields superior sequential model fit and predictive performance compared to viable alternatives.
