---
title: "Solar synthetic imaging: Introducing denoising diffusion probabilistic models on SDO/AIA data"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
date: 2024-03-09
venue: 'Astronomy & Astrophysics'
paperurl: 'http://fpramunno.github.io/files/solar_synthetic_imaging.pdf'
citation: 'Ramunno, F. P., Hackstein, S., Kinakh, V., Drozdova, M., Quétant, G., Csillaghy, A., & Voloshynovskiy, S. (2024). "Solar synthetic imaging: Introducing denoising diffusion probabilistic models on SDO/AIA data." <i>Astronomy & Astrophysics</i>. 686(A285).
'
---

For the luck of humanity, there are way less big solar flares than small ones. Even if these are good news, this makes it challenging to train machine learning algorithms able to model solar activity. As a result, solar monitoring applications, including flare forecasting, suffer from this lack of input data. To overcome this issue, generative deep learning models can be utilised to produce synthetic images representing solar activity and thus compensating the rarity of big events. This study aims to develop a method that can generate synthetic images of the Sun with the ability to include flare of a specific intensity. To achieve our goals, we introduce a Denoising Diffusion Probabilistic Model (DDPM). We train it with a carefully crafted dataset from the Atmospheric Image Assembly (AIA) instrument on the SDO spacecraft, specifically the 171 Å band, which captures images of coronal loops, filaments, flares, and active regions. GOES X-ray measurements are employed to classify each image based on the solar flare scale (A, B, C, M, X), after selecting the flaring images from AIA using the Heliophysics Event Knowledgebase, which allows for temporal localisation of the flaring events. The generative model performance is evaluated using cluster metrics, Fréchet Inception Distance (FID), and the F1-score. We demonstrate state-of-the-art results in generating solar images and conduct two experiments that use the synthetic images. The first experiment trains a supervised classifier to identify those events. The second experiment trains a basic solar flare predictor. The experiments demonstrate the effectiveness of additional synthetic samples to addressing the problem of imbalanced datasets. We believe this is only the beginning of DDPM use with solar data. It remains to gain a better understanding of the generation capabilities of the denoising diffusion probabilistic models in the contest of solar flare predictions and apply them to other deep learning and physical tasks, such as AIA to HMI (Helioseismic and Magnetic Imager) image translation.

<br/><img src='/images/for_back_DDPM (2).png'>

======

<br/><img src='/images/for_back_DDPM (3).png'>
