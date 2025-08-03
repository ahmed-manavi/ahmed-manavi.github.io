---
title: "Radio Frequency Interference Detection for SMAP Radiometer Using Convolutional Neural Networks"
collection: publications
category: manuscripts
permalink: /publication/2022-smap-rfi-cnn
excerpt: 'CNN-based approach for detecting RFI in data collected by NASA’s SMAP microwave radiometer.'
date: 2022-12-01
venue: 'IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 15, pp. 10099-10112'
paperurl: 'https://doi.org/10.1109/JSTARS.2022.3223198'
citation: 'A. M. Alam, M. Kurum, and A. C. Gurbuz, "Radio Frequency Interference Detection for SMAP Radiometer Using Convolutional Neural Networks," in <i>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</i>, vol. 15, pp. 10099-10112, 2022, doi: 10.1109/JSTARS.2022.3223198.'
---

 Passive remote sensing is a crucial technology for climate studies and Earth science. NASA's soil moisture active passive (SMAP) is a remote sensing observatory that uses passive microwave radiometer to measure soil moisture and detect the freeze or thaw state of that area. Despite operating in the protected band of radio spectrum (1400-1427 MHz), the radiometer's measurements are nonetheless tainted by radio frequency interference (RFI). Increasing number of active wireless technologies such as radar signals used in air surveillance, 5G wireless communication and unmanned aerial vehicles are contributing to RFI through either out-of-band emissions or operating in-band illegally. Physical modeling to detect RFI globally might prove to be challenging as RFI can be generated from single as well as multiple sources and these can be divided as pulsed or continuous wave RFI. In this study, a deep learning (DL) based RFI detection method is proposed with novel convolutional neural network framework that can detect different types of RFI on global scale. This is a data-driven approach where detection framework learns directly from the SMAP data products to make a decision whether a certain footprint is RFI contaminated or not. SMAP's level 1A data products that contain antenna counts of different raw moment along with Stokes parameters are used in this study to produce spectrograms and level 1B data products containing the quality flags are used to dynamically label those spectrograms. This study's robust DL framework provided highest accuracy with the raw moments of horizontal polarization (99.99%) to detect RFI globally. 
