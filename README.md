# 3DSTPM-IEEE-TGRS
This is the documentation for the paper"Infrared Small Target Detection Combining Deep Spatial-Temporal Prior with Traditional Priors"
## Algorithm Introduction
### Overall Architecture
![image](https://github.com/ELOESZHANG/3DSTPM-IEEE-TGRS/blob/main/overall.png)
### Abstract
Infrared small target detection is a critical component of infrared search and track (IRST) systems. However, existing traditional methods only rely on traditional priors for detection, while existing deep learning methods depend heavily on training data with fine-grained annotations to obtain data-driven deep priors, which limits their effectiveness in infrared sequence detection. In this study, we propose a spatial-temporal tensor optimization model that combines the strengths of the dataset-free deep prior and traditional priors. On the one hand, we introduce the dataset-free deep spatial-temporal prior expressed by the untrained 3D Spatial-Temporal Prior Module (3DSTPM) to help capture the underlying spatial-temporal characteristics. On the other hand, we present the convolution-based TNN method and Nested Total Variation (NTV) regularization to respectively acquire the low-rank prior and local smoothness prior, aiding in target enhancement and background suppression. Furthermore, we can obtain accurate detection results by using an unsupervised solving algorithm based on the adaptive moment estimation (Adam) algorithm to learn parameters. Comprehensive experiments reveal that the proposed method performs better on real scenes than other state-of-the-art competitive detection approaches.
## Code
The code will be available after the article is accepted.
## Results
### IoU and F-measure
![image](https://github.com/ELOESZHANG/3DSTPM-IEEE-TGRS/blob/main/results-1.png)
### AUC
![image](https://github.com/ELOESZHANG/3DSTPM-IEEE-TGRS/blob/main/results-3.png)
### BSF and SCRG
![image](https://github.com/ELOESZHANG/3DSTPM-IEEE-TGRS/blob/main/result-2.png)
