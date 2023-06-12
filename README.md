# Multi-Branch Shuffle Network with Coordinate Attention for Hyperspectral Image Classification.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Hyperspectral image (HSI) contains rich spatial and
spectral information, which can accurately reflect the spectral
characteristics of targets. As a result, it has been widely applied
in fields such as precision agriculture, object recognition, and
environmental monitoring. However, due to the presence of
substantial noise interference and data redundancy, traditional
convolutional neural networks (CNNs) struggle to achieve precise
classification of hyperspectral images. Although deeper architecture or higher-dimensional of CNN can partially address this
issue, the high computational cost associated with them cannot
be ignored. In this paper, we propose a Multi-branch Shuffle
Network with Coordinate Attention (MSNCA). Our approach
leverages the Depth-wise Atrous Spatial Pyramid (DASP) module
to make the multi-scale feature fuse , significantly improving
information utilization. Additionally, we introduce a coordinate
attention mechanism that effectively mitigates the loss of longrange dependencies caused by convolutions, facilitating the integration of local and global features. We validate our method on
three representative HSI datasets and compare it with state-ofthe-art approaches. The results demonstrate that our proposed
method outperforms other approaches on two of the datasets. 

##Model

![CNN](https://github.com/nightgloooow/MSNCA/assets/90490619/2565eb78-27e2-4d4b-afd8-f374c330f703)

Fig. 1. The structure of proposed MSNCA.

## Prerequisites

- [Anaconda 4.10.1](https://www.anaconda.com/download/#linux)
- [Tensorflow 2.4.1](https://github.com/tensorflow/tensorflow/tree/r2.4)
- [Keras 2.4.3](https://github.com/fchollet/keras)

### Salinas Scene (SS) dataset

![IP-FC](https://github.com/nightgloooow/MSNCA/assets/90490619/f4681f2d-7666-41db-84ba-b9550115d0f5)
![IP-GT](https://github.com/nightgloooow/MSNCA/assets/90490619/bf4829ad-5cc7-47fe-875c-8d25ec5daccd)
![IP-PRE](https://github.com/nightgloooow/MSNCA/assets/90490619/8639902d-0ccc-4ba4-991f-ef330c2d3993)


Fig. 2. Visual classification results on the Indian Pines. (a) False color image.
(b) Ground truth. (c) MSNCA

## Acknowledgement
https://github.com/gokriznastic/HybridSN  
https://github.com/menon92/WaveletCNN
https://github.com/tanmay-ty/SpectralNET

## License

Copyright (c) 2023 Ao Meng and Taosheng Xu. Released under the MIT License. See [LICENSE](LICENSE) for details.
