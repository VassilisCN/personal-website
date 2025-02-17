---
title: Conditional Hand Image Generation using Latent Space Supervision in Random Variable Variational Autoencoders
date: '2024-09-30'
authors:
- admin
- Iason Oikonomidis
- Giorgos Karvounas
- Antonis Argyros
publication_types: ['paper-conference']

abstract: ''
featured: false
publication: '*Proceedings of the IEEE/CVF European Conference on Computer Vision (ECCV) Workshops*'
share: false

tags:
  - Artificial Inteligence
  - Variational Autoencoders
  - Random Variable Modules
  - Synthetic Data
  - Hand Pose

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://hands-workshop.org/files/2024/ECCVW_Hands_2024_CG_SRV_VAE-4.pdf'
url_code: ''
url_dataset: ''
url_poster: 'uploads/ECCV 2024 Hands SRV-VAE Poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Synthesising new hand images, conditioned on hand poses.'
  focal_point: ''
  preview_only: false
---

We introduce a novel framework for generating photorealistic synthetic images of human hands conditioned to a precise pose annotation. We propose a supervised Random Variable Variational Autoencoder (SRV-VAE), a model that disentangles and encodes the appearance and pose of the hand into separate components of the latent space. Appearance, representing individual subject traits, is unsupervised. Hand pose is strictly supervised and yields control over the synthesis process. Leveraging the robust RV VAE variant, our architecture ensures stable training and accurate encoding of complex hand dynamics. Our model is capable of generating hand images of previously unseen hand poses for specific subjects. Experimental results indicate the model’s efficacy in synthesizing realistic and varied hand images, holding significant promise for advancements in both academic research and practical applications such as data upsampling, where accurate hand pose and texture data is critical.