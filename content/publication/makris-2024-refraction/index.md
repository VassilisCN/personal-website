---
title: Refraction-Aware Structure from Motion for Airborne Bathymetry
date: '2024-11-15'
doi: '10.3390/rs16224253'
authors:
- Alexandros Makris
- admin
- Evangelos Alevizos
- Iason Oikonomidis
- Dimitrios D Alexakis
- Anastasios Roussos
publication_types: ["article-journal"]
abstract: ''
featured: false
publication: '*Remote Sensing*'
share: false

tags:
  - Artificial Inteligence
  - Depth Estimation

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: 'https://github.com/amakris/R-SfM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.mdpi.com/2072-4292/16/22/4253'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Method pipeline for estimating Bathymetry'
  focal_point: ''
  preview_only: false
---

In this work, we introduce the first pipeline that combines a refraction-aware structure from motion (SfM) method with a deep learning model specifically designed for airborne bathymetry. We accurately estimate the 3D positions of the submerged points by integrating refraction geometry within the SfM optimization problem. This way, no refraction correction as post-processing is required. Experiments with simulated data that approach real-world capturing conditions demonstrate that SfM with refraction correction is extremely accurate, with submillimeter errors. We integrate our refraction-aware SfM within a deep learning framework that also takes into account radiometrical information, developing a combined spectral and geometry-based approach, with further improvements in accuracy and robustness to different seafloor types, both textured and textureless. We conducted experiments with real-world data at two locations in the southern Mediterranean Sea, with varying seafloor types, which demonstrate the benefits of refraction correction for the deep learning framework. We made our refraction-aware SfM open source, providing researchers in airborne bathymetry with a practical tool to apply SfM in shallow water areas.