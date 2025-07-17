---
title: "Efficient implementation of the adaptive scale pixel decomposition algorithm"
collection: publications
category: manuscripts
permalink: /publication/2016-08-01-paper-title-number-1
excerpt: 'Efficient implementation of the adaptive scale pixel decomposition algorithm'
date: 2016-08-01
venue: 'Astronomy & Astrophysics'
paperurl: 'https://ui.adsabs.harvard.edu/abs/2016A%26A...592A.128Z/abstract'
bibtexurl: 'https://ui.adsabs.harvard.edu/abs/2016A%26A...592A.128Z/exportcitation'
---

**Context**. Most popular algorithms in use to remove the effects of a telescope's point spread function (PSF) in radio astronomy are variants of the CLEAN algorithm. Most of these algorithms model the sky brightness using the delta-function basis, which results in undesired artefacts when used to image extended emission. The adaptive scale pixel decomposition (Asp-Clean) algorithm models the sky brightness on a scale-sensitive basis and thus gives a significantly better imaging performance when imaging fields that contain both resolved and unresolved emission.
**Aims**: However, the runtime cost of Asp-Clean is higher than that of scale-insensitive algorithms. In this paper, we identify the most expensive step in the original Asp-Clean algorithm and present an efficient implementation of it, which significantly reduces the computational cost while keeping the imaging performance comparable to the original algorithm. The PSF sidelobe levels of modern wide-band telescopes are significantly reduced, allowing us to make approximations to reduce the computational cost, which in turn allows for the deconvolution of larger images on reasonable timescales.
**Methods**: As in the original algorithm, scales in the image are estimated through function fitting. Here we introduce an analytical method to model extended emission, and a modified method for estimating the initial values used for the fitting procedure, which ultimately leads to a lower computational cost.
**Results**: The new implementation was tested with simulated EVLA data and the imaging performance compared well with the original Asp-Clean algorithm. Tests show that the current algorithm can recover features at different scales with lower computational cost.