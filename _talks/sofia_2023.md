---
title: "Modelling Solar Images from SDO/AIA with Denoising Diffusion Probabilistic Models"
collection: talks
category: talks
permalink: 
excerpt: ''
date: 2023/4
venue: 'INTERNATIONAL WORKSHOP ON MACHINE LEARNING AND COMPUTER VISION IN HELIOPHYSICS, Sofia (Bulgaria)'
slidesurl: 'http://fpramunno.github.io/files/Sofia_conference_Francesco_Pio_Ramunno.pdf'
citation: 'Francesco Pio Ramunno, Andre Csillaghy. 1(3).'
---

Solar flares have the potential to cause geomagnetic storms, which can endanger astronauts and disrupt airline communications. These disturbances also have an impact on modern technology, specifically high-frequency radio systems. Consequently, there is a need to predict these events, particularly high-energy solar flares such as M- and X-class flares. However, the field of Heliophysics lacks sufficient X-flare data to train a supervised algorithm for flare forecasting, resulting in an unbalanced dataset due to the rarity of these physical events. To overcome this issue, generative deep learning models can be utilized to produce synthetic images representing solar activity. In this study, we trained a denoising diffusion probabilistic model. The dataset was sourced from the AIA instrument on the SDO spacecraft, specifically the 17.1 Å band, which captures images of coronal loops, filaments, flares, and active regions. The GOES X-ray measurements were employed to classify each image based on the solar flare scale (A, B, C, M, X), after selecting the flaring images from the AIA instrument using the HEK dataset, which allows for accurate temporal localization of the flaring events. The generative model's performance was evaluated using cluster metrics, FID, and the F1-score. Cluster metrics enable comparison between the generated image distribution and the real image distribution. We demonstrated state-of-the-art results in generating Sun images and developed an application that utilized these generated images to train a supervised classifier. The addition of synthetic samples was used to demonstrate their effectiveness in addressing the dataset imbalance. As future work, we aim at gaining a better understanding of the generation capabilities of the denoising diffusion probabilistic models and apply them to other deep learning and physical tasks, such as AIA to HMI translation and solar flare prediction. This would allow for a more extensive investigation of these phenomena by leveraging larger datasets.
<br/><img src='/images/342389106_1269369344012251_5668327613608330591_n.jpg'>

<!-- YouTube Video Embed -->
<div style="text-align:center;">
  <iframe width="560" height="315" src="https://www.youtube.com/watch?v=q0juDoWqMAY" frameborder="0" allowfullscreen></iframe>
</div>
