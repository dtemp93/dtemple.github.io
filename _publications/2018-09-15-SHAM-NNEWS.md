---
title: "Synthetic Heterogeneous Anomaly and Maneuver - Neural Network Event Winnowing System"
collection: publications
permalink: /publications/2018-09-SHAM-NNEWS
venue: "Advanced Maui Optical and Space Surveilance Technologies Conference (AMOS 2018)"
excerpt: 'SHAM-NNEWS demonstrates satellite maneuver detection using latitude and longitude over time.'
date: 2018-09-15
paperurl: https://amostech.com/TechnicalPapers/2018/Poster/Temple.pdf
citation: 'Dwight Temple. 2018. Synthetic Heterogeneous Anomaly and Maneuver - Neural Network Event Winnowing System. <i>Advanced Maui Optical and Space Surveilance Technologies Conference 2018</i>.'
---

## Abstract
This paper takes a step towards temporal reasoning in a dynamically changing video, not in the pixel space that constitutes its frames, but in a latent space that describes the non-linear dynamics of the objects in its world. We introduce the Kalman variational auto-encoder, a framework for unsupervised learning of sequential data that disentangles two latent representations: an object's representation, coming from a recognition model, and a latent state describing its dynamics. As a result, the evolution of the world can be imagined and missing data imputed, both without the need to generate high dimensional frames at each time step. The model is trained end-to-end on videos of a variety of simulated physical systems, and outperforms competing methods in generative and missing data imputation tasks.
<div style="text-align:center"><img src="https://raw.githubusercontent.com/simonkamronn/kvae/master/assets/kvae_figure.png" width="300"></div>

## Main result
As shown in the paper, the SHAM-NNEWS can be trained end-to-end, and is able learn a recognition and dynamics model from the videos. The model can be used to generate new sequences, as well as to do missing data imputation without the need to generate high-dimensional frames at each time step.
<div style="text-align:center"><img src="https://raw.githubusercontent.com/simonkamronn/kvae/master/assets/results.png" width="800"></div>