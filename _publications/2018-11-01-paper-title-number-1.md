---
title: "Fast High-fidelity Reconstruction of Radio Interferometric Images"
collection: publications
category: manuscripts
permalink: /publication/2018-11-01-paper-title-number-1
excerpt: 'Fast High-fidelity Reconstruction of Radio Interferometric Images'
date: 2018-11-01
venue: 'Publications of the Astronomical Society of the Pacific'
paperurl: 'https://iopscience.iop.org/article/10.1088/1538-3873/aae4ca/pdf'
bibtexurl: 'https://ui.adsabs.harvard.edu/abs/2018PASP..130k7002Z/exportcitation'
---

This dissertation summary presents advanced deconvolution algorithms for radio interferometric imaging, addressing computational and fidelity challenges in modern arrays (e.g., ALMA, SKA). Key contributions include:  

### **1. Accelerated Adaptive-Scale Deconvolution**  
- Replaces iterative convolution with analytical Gaussian modeling (Eqs. 1–2), achieving **20× faster processing** while preserving quality.  
- Leverages improved *uv*-coverage of next-gen arrays for accurate Gaussian beam approximations.  

### **2. Adaptive Loop Gain Optimization**  
- Introduces dynamic gain adjustment (Eq. 3) to suppress errors in bright/faint regions, **reducing RMS error by 10×**.  
- Extends to scale-free CLEAN, enhancing convergence via SNR-proportional gains.  

### **Results & Implementation**  
- Outperforms Clark-Clean/Asp-Clean in 3C31 reconstructions (Fig. 1), balancing speed and fidelity.  
- Integrated into CASA/Python; C++ port underway.  

**Significance**: Enables high-resolution imaging for large-scale surveys with future arrays.  

*Supported by NRAO, NSF China (11103055), and CAS programs.*  

---  
*Format: Structured for clarity; 150 words (optimized for academic databases).*  