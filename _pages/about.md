---
permalink: /
title: "Yiran (Betty) Yuan"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About Me

I am Yiran (Betty) Yuan, a Statistics senior undergraduate in the Department of Statistics and Data Science at Southern University of Science and Technology (SUSTech). I enjoy using statistical thinking, machine learning, and careful empirical analysis to understand complex scientific and real-world questions.

My work sits at the intersection of statistical methodology, trustworthy machine learning, and scientific discovery. I am especially interested in how knowledge emerges and diffuses through citation networks, how medical imaging models can become more calibrated and reliable, and how evidence can be retrieved and evaluated transparently.

I am an energetic and curious researcher who enjoys learning across fields, working with collaborators, and turning messy data into interpretable evidence.

## Research Interests

- Science of science, citation networks, and knowledge diffusion
- Statistical and computational methods for discovery emergence
- Bayesian uncertainty quantification and calibrated risk prediction
- Trustworthy machine learning under dataset shift
- Medical imaging and statistical evaluation of clinical AI
- Large-scale bibliometric data analysis and evidence retrieval

## News

- **September 30, 2026** — Presented *Evidence-Oriented Mapping of Subjective–Objective Cognitive Dissociation in HIV and Alzheimer’s Disease* at the Penn CFAR Scientific Symposium.
- **September 27, 2026** — *SymBreak: Breaking the Implanted False-Belief to Identify Subvisual Ischemic Changes* is under review at ICLR 2027.
- **2026** — The *Scientific Discovery Birthplaces and Citation Diffusion in Global Knowledge Networks* project is being developed as a working paper.

## Selected Projects

{% include base_path %}
{% assign homepage_projects = site.portfolio | sort: "order" %}
{% for post in homepage_projects %}
  {% include archive-single.html %}
{% endfor %}

## Beyond Research

Outside research, I enjoy travelling, city walks, making coffee and desserts, and dancing.

| Travelling | City walks |
|---|---|
| ![Travelling](/images/interests/travel.jpg) | ![City walks](/images/interests/citywalk.jpg) |

| Coffee and desserts | Dancing |
|---|---|
| ![Coffee and desserts](/images/interests/coffee-desserts.jpg) | ![Dancing](/images/interests/dancing.jpg) |
