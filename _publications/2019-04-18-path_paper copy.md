---
title: "New Path Paper: Path in the world"
date: 2025-03-15
layout: single
categories:
  - research
tags:
  - publication
  - neuroscience
  - EEG
  - affordances
  - scene perception
excerpt: "Our latest study investigates how the human brain and deep neural networks differ in processing locomotive action affordances in visual scenes."
image:
  path: assets/images/jonas-degener-RCS0EKm_yNs-unsplash.jpg
  alt: "EEG study thumbnail"
header:
  overlay_image: assets/images/jonas-degener-RCS0EKm_yNs-unsplash.jpg
  caption: "Photo by Jonas Degener on Unsplash"
  overlay_filter: 0.3
  teaser: /assets/images/ICLR_new.png
  actions:
    - label: "View Abstract"
      url: "https://www.biorxiv.org/content/10.1101/2025.03.14.642994v1.abstract"
    - label: "Download PDF"
      url: "/assets/papers/2025-bartnik-affordance-eeg.pdf"
---


# Human and Deep Neural Network Alignment in Navigational Affordance Perception

**Venue:** First ICLR 2024 Workshop on Representational Alignment (Re-Align), non-archival  
**Authors:** Clemens G. Bartnik & Iris I. A. Groen (University of Amsterdam)  
**Paper:** [OpenReview PDF](https://openreview.net/pdf?id=FS5Lq9Flep)

---

Humans effortlessly navigate the world, selecting different routes and trajectories through complex environments. Research on navigational affordance representations was first advanced by Bonner & Epstein (2017), who proposed that path trajectories provide a natural way to capture how environments guide movement.

Whereas earlier studies focused mainly on indoor settings and walking as the primary action, we broadened the scope by collecting path annotations for a diverse dataset of 231 images, equally divided across indoor, outdoor man-made, and outdoor natural scenes. This allowed us to test whether the layer activations of state-of-the-art deep neural networks (DNNs) align with these aggregated human path representations.

In addition, we used explainable AI methods to probe what kinds of visual information support the networks’ representations—asking whether DNNs capture affordance-relevant structure, or whether their alignment remains dominated by object-based cues.

<p align="center">
  <img src="/assets/images/Path_overview.png" alt="Overview of scene perception approaches" width="1200"><br>
  <em>Overview of object-, space-, and affordance-centered approaches to scene perception.</em>
</p>


To assess the consistency of human path annotations, we used the Fréchet distance as a quantitative measure of similarity between trajectories. This metric confirmed that participants’ paths were highly consistent across images, supporting the idea that the annotations capture meaningful navigational structure rather than noise. While the Fréchet distance has its limitations, the results make clear that these paths are far from random—and provide a valuable benchmark against which to evaluate DNN representations.


## Reference
**Bartnik, C. G., & Groen, I. I. A.** (2024). *Human and Deep Neural Network Alignment in Navigational Affordance Perception.* First ICLR Workshop on Representational Alignment (Re-Align), non-archival. [OpenReview](https://openreview.net/pdf?id=FS5Lq9Flep)

---

