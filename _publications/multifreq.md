---
title: "Multi-frequency asynchronous optical coherence elastography by direct demodulation"
collection: publications
category: manuscripts
permalink: /publication/multifreqOCE
excerpt: 'Asynchronous optical coherence elastography enabled recovery of coherent shear wave fields in conventional frame-rate, raster-scanning OCT systems. Here, we extended our approach to multi-frequency imaging using a direct-demodulation framework that enables isolation of up to 12 simultaneous excitation frequencies, providing efficient measurement of shear wave dispersion and robust mechanical characterization of complex tissues.'
date: 2026-09-01
venue: 'Biomedical Optics Express'
paperurl: 'http://gingerschmidt.github.io/files/Multi-frequency asynchronous optical coherence elastography by direct demodulation.pdf'
---

Optical coherence elastography has demonstrated promising results in highly specialized, research-grade OCT systems and in systems with custom, slow scan patterns. However, these approaches are fundamentally incompatible with commercial, FDA-approved OCT systems already deployed in clinics worldwide. Asynchronous optical coherence elastography addresses this limitation by using raster scanning–induced amplitude modulation to spatially encode harmonic shear wave displacement fields. This principle enables recovery of the coherent shear wave field within seconds using conventional frame-rate systems, despite severe temporal undersampling across B-scans. 

In this work, we extend this approach to show that asynchronous imaging can recover multiple simultaneous excitation frequencies, effectively multiplexing the determination of shear wave dispersion curves. 

We further introduce a new recovery framework, termed direct demodulation, based on the two-dimensional spatial Fourier transform of raster-scanned displacement data. 

We demonstrate experimentally that this framework enables efficient and intuitive isolation of up to 12 excitation frequencies within a single acquisition. We also identify practical limits on frequency multiplexing and provide guidelines and code for selecting imaging and excitation parameters that minimize spectral interference. The framework is validated through agreement between sequential and multiplexed measurements of shear wave number. Finally, we demonstrate the importance of multi-frequency elastography for robust mechanical characterization of complex tissues, showing sensitivity to boundary effects, viscoelastic dispersion, and improved mechanical contrast through incoherent frequency averaging in heterogeneous samples. 

This work enables multi-frequency, shear wave–based OCE in conventional frame-rate, raster-scanning OCT systems, further paving a path toward widespread adoption of elastography in existing imaging platforms.

[Open source code](https://github.com/gingerschmidt/AsyncOCE2D)

[Article link](https://opg.optica.org/boe/fulltext.cfm?uri=boe-17-9-4947)
