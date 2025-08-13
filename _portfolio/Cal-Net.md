---
title: "Deep Learning-Based Radiometer Calibration Framework"
excerpt: "Deep learning-based calibration for passive microwave radiometers using physics-informed architectures<br/><img src='/images/DL_framework_cal.png'>"
collection: portfolio
date: 2023-08-13
venue: "Research Project"
---

![Calibration Framework](/images/DL_framework_cal.png)

Accurate calibration is essential for passive microwave radiometers to ensure reliable retrieval of geophysical parameters such as sea surface temperature, soil moisture, and atmospheric water vapor. Traditional calibration methods rely on periodic reference measurements from hot/cold loads and noise diodes, which can be limited by system drift, environmental conditions, and RFI contamination.

This project presents a **deep learning-based calibration framework** that integrates **time-frequency domain features** with radiometer output to achieve real-time, robust calibration. The architecture is inspired by **U-Net** principles and trained with a **dual-loss strategy**:

- **Mean Squared Error (MSE)** loss enforces accurate Brightness Temperature recovery.
- **Regularization Loss** constrains the solution to physically plausible ranges based on radiometer physics.

## Methodology

The framework processes radiometer outputs and auxiliary measurements, learning a mapping from raw counts to calibrated Brightness Temperatures without requiring frequent hot/cold load references. Physics-informed constraints ensure the model generalizes across varying environmental conditions and hardware states.

## Evaluation

The approach is validated on:

- **Synthetic datasets** simulating system gain drift, non-linearity, and additive noise.
- **Real-world measurements** from an **L-band radiometer** under controlled laboratory and field campaigns.

The deep learning framework demonstrates:

- Reduced calibration error compared to polynomial and statistical methods.
- Robustness to gain fluctuations and partial RFI contamination.
- Real-time inference capability suitable for embedded deployment.

**Read related work:** [IEEE Xplore – RFI-Net](https://ieeexplore.ieee.org/abstract/document/10318952)
