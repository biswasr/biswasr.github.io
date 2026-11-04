---
layout: about
title: About
permalink: /
subtitle: >
  Postdoctoral Scholar · Department of Neurology · Weill Institute for Neurosciences · University of California, San Francisco<br>
  Research Data Scientist · San Francisco VA Health Care System

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

announcements:
  enabled: true
  scrollable: false
  limit: 20
selected_papers: true
social: true
---

I develop causal and interpretable machine learning methods for neuroscience and medicine. I design these methods around the structure of each problem. In neuroscience this means modeling directed neural interactions that act across several time lags, and accounting for the other recorded neurons so that indirect influences are not mistaken for direct ones. In medicine it means deciding with clinicians what a model should assess and what it must handle, such as the technique errors that distort blood pressure readings, or the artifacts in everyday skin photos. I also keep assumptions light, using nonparametric tests where possible, and computation fast, using GPU acceleration, so the methods scale to large datasets and can support real-time use.

These methods produce explanations, such as which neurons drive which, or which cues drive an AI system's decision. I then test them against independent evidence. For example, I compare connections inferred from neural activity with synaptic wiring measured by electron microscopy and, in ongoing collaborations, with the results of perturbation experiments. In medicine I check that an AI system relies on cues clinicians would assess and stays accurate under real-world conditions.

**Computational Neuroscience.** Applied to more than 57,000 neurons in [mouse visual cortex](https://doi.org/10.64898/2026.03.31.715474), my method [CITS](https://doi.org/10.48550/arXiv.2508.01920) inferred connections that aligned with the synaptic wiring in the electron-microscopy connectome far more closely than Granger causality or lagged correlation, and revealed how this circuitry reorganizes with arousal. Current projects include directed network dynamics of chronic pain with [Dr. Prasad Shirvalkar](https://www.shirvalkarlab.com/), and AI-based reconstruction of visual experience from fMRI with the [Gallant Lab](https://gallantlab.org/) (UC Berkeley).

**Computational Clinical Diagnostics.** With [Dr. Julio Lamprea](https://profiles.ucsf.edu/julio.lampreamontealegre) (UCSF Cardiovascular Prevention Center), I developed [Coach-BP](https://doi.org/10.64898/2026.10.29.26366628), a computer vision system that detects errors in blood pressure measurement technique from clinic video. With [Dr. Maria Wei](https://weilab.ucsf.edu/) (UCSF Dermatology and SF VA), I am developing skin-lesion classifiers that stay accurate when photographs contain common artifacts.

Before joining [Dr. Reza Abbasi-Asl's lab](https://abbasilab.org/) at UCSF, I completed my PhD in Electrical and Computer Engineering (with a secondary MS in Statistics) at the University of Washington, advised by [Dr. Eli Shlizerman](https://faculty.washington.edu/shlizee/), with dissertation [*Causal Functional Connectivity from Neural Dynamics*](https://digital.lib.washington.edu/server/api/core/bitstreams/4e946c85-b002-418d-bf17-fa1d8549ab71/content). Before that, I earned a BS and MS in Statistics at the Indian Statistical Institute, Kolkata.

I also maintain open-source implementations of my methods, including [CITS](https://github.com/abbasilab/cits) and [TimeAwarePC](https://github.com/shlizee/TimeAwarePC).

Feel free to reach out at [rahul.biswas@ucsf.edu](mailto:rahul.biswas@ucsf.edu).
