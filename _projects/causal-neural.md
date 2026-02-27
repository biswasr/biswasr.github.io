---
layout: page
title: Causal Inference in Neural Time Series
description: Nonparametric statistical frameworks for discovering causal structure in high-resolution neural recordings
img: assets/img/research/causal-neural.png
importance: 1
category: Computational Neuroscience
related_publications: biswas2025cits, biswas2023consistent, biswas2022tpc, biswas2022comparative
---

Understanding how neural activity propagates across brain regions requires going beyond correlation — we need to identify *directed*, *causal* relationships from neural recordings.

**The challenge.** Neural time series (fMRI, EEG, ECoG, calcium imaging) are high-dimensional, non-stationary, and exhibit complex lag structures. Classical causal discovery methods make strong parametric assumptions that are often violated in neural data.

**Our approach.** I develop nonparametric causal inference frameworks tailored to neural time series:

- **CITS** (Causal Inference in Time Series): A nonparametric statistical framework for high-resolution neural recordings (in review, *Nature Communications*). CITS enables principled discovery of directed functional circuitry without restrictive parametric assumptions, scaling to the thousands of neurons recorded by modern probes.

- **TPC** (Time-Aware PC Algorithm): A consistent causal discovery method that explicitly models temporal structure in neural data, with formal statistical guarantees ([*PLoS Computational Biology*, 2022](https://doi.org/10.1371/journal.pcbi.1010653); [*Statistics and Computing*, 2023](https://doi.org/10.1007/s10994-019-05810-5)).

**Applications.** These methods have been applied to map directional functional connectivity differences in **Alzheimer's disease and Mild Cognitive Impairment** from fMRI ([*Frontiers in Computational Neuroscience*, 2023](https://doi.org/10.3389/fncom.2023.1020096)), and to characterize directed network dynamics in the mouse visual cortex from Allen Institute electrophysiology datasets.
