---
title: "A Model Estimator for Noisy Compact Emission Recovery in Radio Synthesis Imaging"
collection: publications
category: manuscripts
permalink: /publication/2023-08-01-paper-title-number-5
excerpt: 'An improved CLEAN-based algorithm was proposed to address the precise reconstruction of compact emission in noisy environments, particularly for the challenges in Stokes-I imaging'
date: 2023-08-01
venue: 'The Astronomical Journal'
paperurl: 'https://ui.adsabs.harvard.edu/abs/2023AJ....166...53Z/abstract'
bibtexurl: 'https://ui.adsabs.harvard.edu/abs/2023AJ....166...53Z/exportcitation'

---

Reconstruction of a noisy compact emission must consider not only the point-spread function but also the effect of noise. However, the traditional threshold method in widely-used CLEAN-based algorithms finds it difficult to effectively prevent noise in the model image during noisy compact-emission reconstruction. This significantly limits the performance in noisy compact-emission reconstruction, such as deep field imaging. There are two major difficulties in the accurate reconstruction of a Stokes-I image of compact emission: first, the threshold method that has been used in practice is difficult to use to separate compact emission and noise; and second, over-subtraction makes it difficult for the reconstructed Stokes-I model image to remain positive. Therefore, a filter-based denoizing mechanism is introduced in the search phase of the model components to separate signal and noise so that the signal can be effectively extracted. The relatively larger loop gain for positive components means that the reconstructed model is in line with astrophysics. This will reduce the errors between the true sky image and the model image. The new model estimator is tested on a simulated JVLA observation with realistic source distributions from the VLA Low-Frequency Sky Survey project and the SKADS/SCubed simulation. The experiments show that it is very effective when used to separate signal and noise to lower the noise in the model image. This work explores the use of existing common software CASA to achieve high dynamic range imaging, which is an important step toward square kilometer array data processing.