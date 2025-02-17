---
title: 'RV-VAE: Integrating Random Variable Algebra into Variational Autoencoders'
date: '2023-10-01'
doi: '10.1109/ICCVW60793.2023.00027'
authors:
- admin
- Iason Oikonomidis
- Antonis Argyros
publication_types: ['paper-conference']

abstract: ''
featured: true
publication: '*Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops*'
share: false

tags:
  - Artificial Inteligence
  - Variational Autoencoders
  - Random Variable Modules

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Supplementary Material
  url: https://openaccess.thecvf.com/content/ICCV2023W/VIPriors/supplemental/Nicodemou_RV-VAE_Integrating_Random_ICCVW_2023_supplemental.pdf

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2023W/VIPriors/papers/Nicodemou_RV-VAE_Integrating_Random_Variable_Algebra_into_Variational_Autoencoders_ICCVW_2023_paper.pdf'
url_code: 'https://github.com/VassilisCN/RV-VAE'
url_dataset: ''
url_poster: 'uploads/ICCV 2023 VIPriors RV-VAEs Poster.pdf'
url_project: ''
url_slides: ''
url_source: 'https://openaccess.thecvf.com/content/ICCV2023W/VIPriors/html/Nicodemou_RV-VAE_Integrating_Random_Variable_Algebra_into_Variational_Autoencoders_ICCVW_2023_paper.html'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'RV-VAE Concept Figure'
  focal_point: ''
  preview_only: false
---

Among deep generative models, variational autoencoders (VAEs) are a central approach in generating new samples from a learned, latent space while effectively reconstructing input data. The original formulation requires a stochastic sampling operation, implemented via the reparameterization trick, to approximate a posterior latent distribution. In this paper, we introduce a novel approach that leverages the full distributions of encoded input to optimize the model over the entire range of the data, instead of discrete samples. We treat the encoded distributions as continuous random variables and use operations defined by the algebra of random variables during decoding. This approach integrates an innate mathematical prior into the model, helping to improve data efficiency and reduce computational load. Experimental results across different datasets and architectures confirm that this modification enhances VAE-based architectures'' performance. Specifically, our approach improves the reconstruction error and generative capabilities of several VAE architectures, as measured by the Frechet Inception Distance (FID) metric, while exhibiting similar or better training convergence behavior. Our method exemplifies the power of combining deep learning with inductive priors, promoting data efficiency and less reliance on brute-force learning.