---
title: "Representation of Locomotive Affordances in Brains and Models"
date: 2024-07-14
layout: single
categories:
  - research
tags:
  - publication
  - neuroscience
  - fMRI
  - affordances
  - scene perception
  - deep learning
excerpt: "Our fMRI and behavioral study, published in PNAS, reveals that human visual cortex distinctly represents locomotive affordances in scenes—beyond what current DNNs can model."
image:
  path: assets/images/michael-olsen-YWxfEBlvoiI-unsplash.jpg
  alt: "Thumbnail of fMRI study on action affordances"
header:
  overlay_image: assets/images/michael-olsen-YWxfEBlvoiI-unsplash.jpg
  caption: "Photo by Michael Olsen on Unsplash"
  overlay_filter: 0.5
  teaser: /assets/images/PNAS_new.png
  actions:
    - label: "View Paper"
      url: "https://doi.org/10.1073/pnas.2414005122"
    - label: "Download PDF"
      url: "/assets/papers/2024-bartnik-affordances-fmri.pdf"
---

# Representation of locomotive action affordances in human behavior, brains and deep neural networks  

**Published as:**  
Bartnik, C. G., Sartzetaki, C., Puigseslloses Sanchez, A., Molenkamp, E., Bommer, S., Vukšić, N., & Groen, I. I. A. (2024). *Distinct representation of locomotive action affordances in human behavior, brains and deep neural networks.* *Proceedings of the National Academy of Sciences (PNAS).*  
Published in PNAS: [PNAS, 2024](https://doi.org/10.1073/pnas.2414005122)  

This study was also featured in a press release from the University of Amsterdam:  
[What the human brain can do that AI can’t](https://www.uva.nl/en/content/news/press-releases/2025/06/what-the-human-brain-can-do-that-ai-cant.html)  

---

## Overview  
When we look at a scene—a mountain trail, a swimming pool, or a city street—we instantly know how we could move through it: walking, swimming, cycling, or perhaps not at all. This seemingly effortless judgment, known as *locomotive affordance perception*, motivated our research. We asked: how does the brain represent these action possibilities, and can current AI models capture them?  

To answer this, we combined three approaches (see figure below): behavioral annotations of action possibilities, fMRI measurements of brain activity, and computational modeling with deep neural networks. Participants viewed hundreds of real-world indoor and outdoor images and indicated which actions each environment afforded. At the same time, we measured brain activity in scene-selective regions such as the parahippocampal place area (PPA) and occipital place area (OPA). We then compared these human data to a wide range of neural networks, from convolutional models to multimodal vision–language systems like CLIP and GPT-4.  

<p align="center">
  <img src="/assets/images/15ca0ed1-b697-4fa6-8f57-f2233b0153ea.png" alt="Overview of methods and results for affordance study" width="1000"><br>
  <em>Study design: examples of stimuli, behavioral annotation tasks, fMRI responses, DNN activations, and representational similarity analysis (RSA).</em>
</p>

To link these different data sources, we used *Representational Similarity Analysis (RSA)*—a method that compares the structure of responses across images to test whether brains, behaviors, and models organize scenes in the same way.  

---

## What we found  
Behavioral ratings revealed that people cluster environments into structured dimensions of action possibilities—roughly separating land-based, water-based, and climbing-related movements. Crucially, fMRI data showed that PPA and OPA encode these affordances automatically, even when participants were not explicitly thinking about actions. In the figure, this corresponds to the colored brain maps and bar plots demonstrating significant RSA correlations for affordances in PPA and OPA.  

When we turned to AI models, the gap became clear. Classic convolutional networks aligned well with object-based information but poorly with action affordances. Vision transformers and multimodal models improved alignment somewhat, especially when trained with affordance labels or language embeddings, yet none fully captured the structure observed in human brains and behavior. The figure illustrates these comparisons, showing how DNNs and GPT-4 outputs correlate more strongly with object representations than with affordances.  

---

## Why this matters  
These results demonstrate that the brain’s visual system represents not only *what* is in a scene but also *what can be done* within it. Affordance perception is a fundamental and automatic property of human vision that current AI models only approximate. By better understanding how the brain encodes action possibilities, we may find new pathways to develop AI systems that are more efficient, sustainable, and aligned with human ways of interacting with the world.  

---

## Highlights from research  
- fMRI reveals that both OPA and PPA encode locomotive affordances, beyond object identity or surface features.  
- Affordances are represented automatically, independent of task demands.  
- Current DNNs capture some aspects of affordance structure but fall short of human behavior and brain representations.  
- Training on affordance labels or using affordance-centered language improves alignment, but important gaps remain.  

---

[Read the preprint on bioRxiv](https://doi.org/10.1101/2024.05.15.594298)  
[Download the PDF](/assets/papers/2024-bartnik-affordances-fmri.pdf)  
[Read the UvA press release](https://www.uva.nl/en/content/news/press-releases/2025/06/what-the-human-brain-can-do-that-ai-cant.html)  

