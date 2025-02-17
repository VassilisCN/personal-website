---
title: Single-shot 3D hand pose estimation using radial basis function networks trained on synthetic data
date: '2019-02-27'
doi: '10.1007/s10044-019-00801-7'
authors:
- admin
- Iason Oikonomidis
- Antonis Argyros
publication_types: ["article-journal"]
abstract: ''
featured: false
publication: '*Pattern Analysis and Applications*'
share: false

tags:
  - Hand Pose
  - Synthetic Data

# Display this page in the Featured widget?
featured: true

url_pdf: 'http://xanthippi.ceid.upatras.gr/HealthSign/resources/Publications/2019_journal_PAA_Nicodemou.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/article/10.1007/s10044-019-00801-7'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Method workflow for training RBFNs on rotations and articulations.'
  focal_point: ''
  preview_only: false
---

In this work, we present a novel framework to perform single-shot hand pose estimation using depth data as input. The method follows a coarse to fine strategy and employs several radial basis function networks (RBFNs) that are trained on a dataset containing only synthetically generated depth maps. Thus, compared to most contemporary deep learning approaches, it does not require the laborious annotation of large, real-world datasets. At run time, an initialization RBFN is used to provide a rough estimation of the hand’s 3D pose. Subsequently, several specialized RBFNs are employed to improve that initial estimation in an iterative refinement scheme. To train the RBFNs, we select a set of hand poses from a real-world sequence that are as diverse as possible. We use this representative set, along with a dense sampling of all possible rotations, as a seed to generate a large synthetic training set. The method is parallelizable, taking advantage of the inherent data parallelism of RBFNs. Furthermore, the method requires few real-world data and virtually no manual annotation. We perform a quantitative evaluation of our method on a testing sequence of our own. We also present quantitative and qualitative results on a public dataset that is commonly used to evaluate hand pose estimation and tracking methods. We show that in all cases, our approach achieves promising results. Moreover, it can achieve comparable or even faster computational performance than current deep learning approaches but on a single CPU core, i.e., without requiring GPU processing.