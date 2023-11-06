---
layout: project
title: 'Caltech SURF, Exposure Time Calculator (ETC) for Keck‑HISPEC and TMT‑MODHIS'
caption: Research
description: >This project provides an update of the SNR and exposure time calculation tool and its web platform for Keck-HISPEC as well as TMT-MODHIS.
date: 12 June, 2023 - Present
image: 
  path: /assets/img/p2ur.png
accent_color: '#4fb1ba'
theme_color: '#193747'
sitemap: false
---
Specsim is a Python package for simulating spectroscopic observations with TMT-MODHIS and Keck-HISPEC, which are both high-resolution (R~100,000) diffraction limited spectrographs covering y, J, H, and K bands simultaneously. Specsim employs Phoenix and Sonora models to simulate stars and planets both for on-axis targets and for off-axis targets, when speckle noise from the host star must be considered. Both simulators implement up-to-date instrument throughput budgets and simulated coupling efficiencies that take into account performance estimates of each telescope's adaptive optics system. The simulators compute the total number of photons arriving at the detector per second and the associated noise level as well as the associated radial velocity precision per order and cross correlation function signal-to-noise ratio (SNR). We present HISPEC and MODHIS performance estimates calculated with specsim and show how it compares to its predecessor code, PSISIM. With minor tweaks, the code can be adapted to compute SNR estimates of other high resolution instruments. We present comparisons between specsim and the KPF and NEID exposure time calculators. A Web Platform for specsim is in development to serve the broader community. These platforms aim to provide users of TMT-MODHIS and Keck-HISPEC an exposure time calculator and simulated spectra for planning observations with the instruments across varied observing scenarios and science cases.
