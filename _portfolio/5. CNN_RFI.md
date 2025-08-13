---
title: "CNN-Based RFI Detection for SMAP Radiometer"
excerpt: "Convolutional neural network approach for robust radio-frequency interference detection in spaceborne L-band radiometer measurements<br/><img src='/images/flowchart_final_all.png'>"
collection: portfolio
weight: 6
venue: "Research Project"
---

![CNN RFI Detection Framework](/images/flowchart_final_all.png)

Radio-frequency interference (RFI) poses a significant challenge for the **Soil Moisture Active Passive (SMAP)** mission’s L-band radiometer, which measures natural microwave emissions from the Earth’s surface for soil moisture and freeze/thaw state retrievals. While SMAP employs onboard and ground-based algorithms for RFI detection, these methods can struggle with weak or non-stationary interference patterns.

This project introduces a **convolutional neural network (CNN)** approach for automated RFI detection, trained on **time–frequency (TF) representations** of SMAP radiometer data. The CNN learns to classify TF bins as contaminated or clean, enabling finer-grained detection than traditional threshold-based algorithms.

## Methodology

- **Input Representation:**  
  SMAP’s Level 1B radiometer data is transformed into spectrograms capturing power variations across frequency and time.
  
- **CNN Architecture:**  
  A multi-layer convolutional model extracts spatial–spectral features from the TF input to identify RFI patterns.

- **Training Data:**  
  The network is trained on labeled datasets containing both RFI-contaminated and clean TF samples, derived from known SMAP overpasses in RFI-heavy and RFI-free regions.

- **Output:**  
  Binary classification masks marking contaminated TF bins, enabling selective removal before geophysical retrieval.

## Evaluation

- **Performance:**  
  Achieves higher detection accuracy, precision, and recall than SMAP’s operational kurtosis and threshold methods.

- **Robustness:**  
  Effective against varying interference types, including continuous wave, pulsed, and frequency-hopping signals.

- **Impact on Science Data:**  
  Improves brightness temperature retrieval accuracy, especially in moderate RFI environments where legacy methods underperform.

## Impact

By integrating deep learning into SMAP’s RFI mitigation pipeline, this work demonstrates the potential for **spaceborne AI-enhanced signal cleaning**. The framework could be adapted to other passive sensing missions operating in congested spectrum bands.

**Read the full paper:** [IEEE Xplore – CNN-Based RFI Detection for SMAP Radiometer](https://ieeexplore.ieee.org/document/9954900)
