---
title: Integration of Photogrammetric and Spectral Techniques for Advanced Drone-Based
  Bathymetry Retrieval Using a Deep Learning Approach
date: '2022-08-24'
doi: "10.3390/rs14174160"
authors:
- Evangelos Alevizos
- admin
- Alexandros Makris
- Iason Oikonomidis
- Anastasios Roussos
- Dimitrios D Alexakis
publication_types: ["article-journal"]
abstract: ''
featured: true
publication: '*Remote Sensing*'
share: false

tags:
  - Artificial Inteligence
  - Depth Estimation

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.mdpi.com/2072-4292/14/17/4160'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Workflow of the proposed approach.'
  focal_point: ''
  preview_only: false
---


  Shallow bathymetry mapping using proximal sensing techniques is an active field of research that offers a new perspective in studying the seafloor. Drone-based imagery with centimeter resolution allows for bathymetry retrieval in unprecedented detail in areas with adequate water transparency. The majority of studies apply either spectral or photogrammetric techniques for deriving bathymetry from remotely sensed imagery. However, spectral methods require a certain amount of ground-truth depth data for model calibration, while photogrammetric methods cannot perform on texture-less seafloor types. The presented approach takes advantage of the interrelation of the two methods, in order to predict bathymetry in a more efficient way. Thus, we combine structure-from-motion (SfM) outputs along with band-ratios of radiometrically corrected drone images within a specially designed deep convolutional neural network (CNN) that outputs a reliable and robust bathymetry estimation. To achieve effective training of our deep learning system, we utilize interpolated uncrewed surface vehicle (USV) sonar measurements. We perform several predictions at three locations in the southern Mediterranean Sea, with varying seafloor types. Our results show low root-mean-square errors over all study areas (average RMSE ≅ 0.3 m), when the method was trained and tested on the same area each time. In addition, we obtain promising cross-validation performance across different study areas (average RMSE ≅ 0.9 m), which demonstrates the potential of our proposed approach in terms of generalization capabilities on unseen data. Furthermore, areas with mixed seafloor types are suitable for building a model that can be applied in similar locations where only drone data is available.