---
layout: project
title: 'OSU-URAP: Quantifying the Ability of JWST and E‑ELT to Detect Biosignatures in the Atmosphere of Exoplanets.'
caption: Research
description: >
  We evaluate the ability of ELT-METIS and ELT-HARMONI to directly image the atmospheres of exoplanets and provide their comparison with JWST/NIRSpec.
  Date: 12 May, 2022 - Present
image: 
  path: /assets/img/p1ur.png
links:
  - title: Research Report
    url: https://aas242-aas.ipostersessions.com/Default.aspx?s=6F-09-20-A9-EB-5D-C2-1A-94-F0-E5-77-46-BD-8C-83&pdfprint=true&guestview=true
accent_color: '#4fb1ba'
theme_color: '#193747'
sitemap: false
---
Based on [NASA](https://exoplanetarchive.ipac.caltech.edu/overview/trappist-1e) publicly available data, we assume that TRAPPIST-1~e has the atmosphere of Modern Earth and Archean Earth.

We use [PICASO](https://natashabatalha.github.io/picaso/) and [petitRADTRANS](https://petitradtrans.readthedocs.io/en/latest/) for simulating the transmission spectra of TRAPPIST-1 e and use PandExo for simulating JWST observation results of TRAPPIST-1~e

Based on the [method](https://iopscience.iop.org/article/10.3847/1538-4357/ac29be) proposed by [Caprice Phillips](https://capricephillips.github.io) and Dr. [Ji Wang](https://www.jiwang.io) to quantify the ability of JWST and ELT to detect a single gas biosignature in the atmosphere of exoplanets, we proposed a method to detect the ability of JWST and ELT to detect a gas pair biosignatures.

We use the [BT-Settl](http://astro.vaporia.com/start/btsettl.html) model to simulate the flux of TRAPPIST-1, assuming that TRAPPIST-1 e has an Earth-like albedo(Modern), and use the [method](https://iopscience.iop.org/article/10.3847/1538-3881/aa6474) proposed by Dr. [Ji Wang](https://www.jiwang.io/) and Dr. [Dimitri Mawet](https://pma.caltech.edu/people/dimitri-mawet) et al. to simulate the results of ELT direct imaging of TRAPPIST-1~e.

The main language of the project is Python, and the main libraries used in this project are PICASO, PandExo, petitRADTRANS, Astropy, NumPy, Pandas, and Matplotlib.

This project was selected by [Undergraduate Research Apprenticeship Program(URAP)](https://ugresearch.osu.edu/current-researchers/funding-opportunities/undergraduate-research-apprenticeship-program-urap) of Ohio State University and was awarded a three-month(May - July, 2022) research fellowship for a total of \$6,000(Approx)
