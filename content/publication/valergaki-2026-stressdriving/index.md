---
title: Combining Facial Videos and Biosignals for Stress Estimation During Driving
date: '2026-01-07'
authors:
- Paraskevi Valergaki
- admin
- Iason Oikonomidis
- Antonis Argyros
- Anastasios Roussos
publication_types: ['paper-conference']

abstract: ''
featured: false
publication: '*Proceedings of the International Conference on Pattern Recognition (ICPR 2026)*'
share: false

tags:
  - Artificial Inteligence
  - Stress Estimation

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://users.ics.forth.gr/~argyros/mypapers/2026_01_arxiv_Stress.pdf'
url_code: 'https://github.com/vivianval/Stress-Estimation-Distracted-Driving-'
url_dataset: ''
url_poster: ''
url_project: 'https://vivianval.github.io/stress_driving.html/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Cross-modal attention fusion architecture for integrating 3D-derived facial features with biosignals.'
  focal_point: ''
  preview_only: false
---

Reliable stress recognition is critical in applications such as medical monitoring and safety-critical systems, including real-world driving. While stress is commonly detected using physiological signals such as perinasal perspiration and heart rate, facial activity provides complementary cues that can be captured unobtrusively from video. We propose a multimodal stress estimation framework that combines facial videos and physiological signals, remaining effective even when biosignal acquisition is challenging. Facial behavior is represented using a dense 3D Morphable Model, yielding a 56-dimensional descriptor that captures subtle expression and head-pose dynamics over time. To investigate the correlation between stress and facial motions, we perform extensive experiments involving also physiological markers. Paired hypothesis tests between baseline and stressor phases show that 38 of 56 facial components exhibit consistent, phase-specific stress responses comparable to physiological markers. Building on these findings, we introduce a Transformer-based temporal modeling framework and evaluate unimodal, early-fusion, and cross-modal attention strategies. Combining 3D-derived facial features with physiological signals via cross-modal attention substantially improves performance over physiological signals alone, increasing AUROC from 52.7% and accuracy from 51.0% to 92.0% and 86.7%, respectively. Although evaluated on driving data, the proposed framework and protocol may readily generalize to other stress estimation settings.