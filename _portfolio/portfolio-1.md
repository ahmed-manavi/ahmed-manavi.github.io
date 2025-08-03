---
title: "RFI-Net: Deep Learning-Based RFI Detection in the Time-Frequency Domain"
collection: portfolio
permalink: /portfolio/rfi-net
excerpt: "Deep learning-based RFI detection and mitigation for passive sensing using a dual-loss U-Net architecture."
date: 2025-08-03
venue: "Research Project"
---

![RFI-Net Overview](/images/over_rfi_net_final.png)

Radio-frequency interference (RFI) poses a significant challenge to passive sensing, which relies on extremely sensitive measurements of natural thermal emissions. As radiometers increasingly operate in spectrally congested environments, often outside protected bands, accurate RFI detection becomes critical to ensure data integrity and enable spectrum coexistence.

This paper presents **RFI-Net**, a deep learning-based framework for RFI detection and mitigation in the time-frequency (TF) domain. The model employs a **U-Net architecture** trained with a physics-informed dual-loss strategy:

- **Binary Cross-Entropy (BCE)** loss targets detection of RFI-contaminated TF bins.
- **Mean Squared Error (MSE)** loss minimizes deviation in estimated Brightness Temperature after RFI suppression.

By removing corrupted bins and using only uncontaminated TF data, the framework enables reliable estimation of Brightness Temperature.

RFI-Net is evaluated on a synthetic dataset simulating multiple interference scenarios with varying interference-to-noise ratios (INRs), spectral occupancy, duty cycles, and waveform types (pulsed & continuous). Real-world validation is performed using a spectrum coexistence testbed dataset, where an **L-band radiometer** is exposed to 5G signals with different power levels and RB group allocations.

Compared to **spectral kurtosis**, RFI-Net achieves superior performance in accuracy, precision, recall, and Brightness Temperature MSE.
