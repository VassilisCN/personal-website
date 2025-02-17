---
title: Learning to infer the depth map of a hand from its color image
date: '2020-07-20'
doi: '10.1109/IJCNN48605.2020.9206925'
authors:
- admin
- Iason Oikonomidis
- Georgios Tzimiropoulos
- Antonis Argyros
publication_types: ['paper-conference']
abstract: ''
featured: false
publication: '*2020 International Joint Conference on Neural Networks (IJCNN)*'
share: false

tags:
  - Artificial Inteligence
  - Depth Estimation
  - Hand Pose

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/9206925'
url_video: 'https://youtu.be/q0sw8dZ3LlU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Hand Depth Estimation from RGB, and application concepts.'
  focal_point: ''
  preview_only: false
---

We present the first direct approach targeted explicitly on human hands that infers depth from monocular RGB images. We achieve this with a Convolutional Neural Network (CNN) that employs a stacked hourglass model as its main building block. Intermediate supervision is used in several outputs of the proposed architecture in a staged approach. To aid the process of training and inference, hand segmentation masks are also estimated in such intermediate supervision steps, and used to guide the subsequent depth estimation process. In order to train and evaluate the proposed method we compile and make publicly available HandRGBD, a new dataset of 20,601 views of hands, each consisting of an RGB image and an aligned depth map. Based on HandRGBD, we explore variants of the proposed approach in an ablative study and determine the most accurate one. The results of an extensive experimental evaluation demonstrate that hand depth estimation from a single RGB frame can be achieved with an accuracy of 22mm, which is comparable to the accuracy achieved by contemporary low-cost depth cameras. Such a 3D reconstruction of hands based on RGB information is valuable as a final result on its own right, but also as an input to several other hand analysis and perception algorithms that require depth input. In this context, the proposed approach bridges the gap between RGB and RGBD, by making all existing RGBD-based methods applicable to RGB input.