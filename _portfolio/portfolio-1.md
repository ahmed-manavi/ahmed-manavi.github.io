---
title: "RFI-Net: Deep Learning-Based RFI Detection in the Time-Frequency Domain"
collection: portfolio
permalink: /portfolio/rfi-net
excerpt: "Deep learning-based framework for RFI detection and mitigation using U-Net in the TF domain."
date: 2025-08-03
venue: "Research Visualization"
---

<embed src="/files/rfi-net-overview.pdf" type="application/pdf" width="100%" height="600px" />

Radio-frequency interference (RFI) poses a significant challenge to passive sensing, which relies on extremely sensitive measurements of natural thermal emissions. As radiometers increasingly operate in spectrally congested environments, often outside protected bands, accurate RFI detection becomes critical to ensure data integrity and enable spectrum coexistence.

This project presents **RFI-Net**, a deep learning-based framework for RFI detection and mitigation in the time-frequency (TF) domain. The model employs a **U-Net architecture** trained with a physics-informed dual-loss strategy:

- **Binary Cross-Entropy (BCE)** for detecting RFI-contaminated TF bins.
- **Mean Squared Error (MSE)** for minimizing Brightness Temperature deviations.

RFI-Net is tested across synthetic and real-world datasets, including L-band radiometers exposed to 5G signals. The method significantly outperforms traditional techniques like spectral kurtosis.

📎 [View High-Resolution Overview PDF](/files/rfi-net-overview.pdf){:target="_blank"}
