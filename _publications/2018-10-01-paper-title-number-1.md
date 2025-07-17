---
title: "Fused CLEAN deconvolution for compact and diffuse emission"
collection: publications
category: manuscripts
permalink: /publication/2018-10-01-paper-title-number-1
excerpt: 'Fused CLEAN deconvolution for compact and diffuse emission'
date: 2018-10-01
venue: 'Astronomy & Astrophysics'
paperurl: 'https://ui.adsabs.harvard.edu/abs/2018A%26A...618A.117Z/abstract'
bibtexurl: 'https://ui.adsabs.harvard.edu/abs/2018A%26A...618A.117Z/exportcitation'
---

**Context**. CLEAN algorithms are excellent deconvolution solvers that remove the sidelobes of the dirty beam to clean the dirty image. From the point of view of the scale, there are two types: scale-insensitive CLEAN algorithms, and scale-sensitive CLEAN algorithms. Scale-insensitive CLEAN algorithms perform excellently well for compact emission and perform poorly for diffuse emission, while scale-sensitive CLEAN algorithms are good for both point-like emission and diffuse emission but are often computationally expensive. However, observed images often contain both compact and diffuse emission. An algorithm that can simultaneously process compact and diffuse emission well is therefore required.

**Aims**: We propose a new deconvolution algorithm by combining a scale-insensitive CLEAN algorithm and a scale-sensitive CLEAN algorithm. The new algorithm combines the advantages of scale-insensitive algorithms for compact emission and scale-sensitive algorithms for diffuse emission. At the same time, it avoids the poor performance of scale-insensitive algorithms for diffuse emission and the great computational load of scale-sensitive algorithms for compact emission in residuals.

**Methods**: We propose a fuse mechanism to combine two algorithms: the Asp-Clean2016 algorithm, which solves the computationally expensive problem of convolution operation in the fitting procedure, and the classical Högbom CLEAN (Hg-Clean) algorithm, which is faster and works equally well for compact emission. It is called fused CLEAN (fused-Clean) in this paper.

**Results**: We apply the fused-Clean algorithm to simulated EVLA data and compare it to widely used algorithms: the Hg-Clean algorithm, the multi-scale CLEAN (Ms-Clean), and the Asp-Clean2016 algorithm. The results show that it performs better and is computationally effective.

This dissertation summary presents advanced deconvolution algorithms for radio interferometric imaging, addressing computational and fidelity challenges in modern arrays (e.g., ALMA, SKA). Key contributions include:  

