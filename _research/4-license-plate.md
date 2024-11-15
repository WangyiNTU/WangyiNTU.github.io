---
title: "2021, IEEE TITS, High-performing Automatic License Plate Recognition"
layout: single-portfolio
excerpt: "<img src='/images/research/License-plate.png' alt=''>"
collection: research
order_number: 5
header: 
  og_image: "research/Two-ACIR.png"
---

![](/images/research/Two-ACIR.png)

In this paper, we propose a real-time and accurate automatic license plate recognition (ALPR) approach. Our study illustrates the outstanding design of ALPR with four insights: (1) the resampling-based cascaded framework is beneficial to both speed and accuracy; (2) the highly efficient license plate recognition should abundant additional character segmentation and recurrent neural network (RNN), but adopt a plain convolutional neural network (CNN); (3) in the case of CNN, taking advantage of vertex information on license plates improves the recognition performance; and (4) the weight-sharing character classifier addresses the lack of training images in small-scale datasets. Based on these insights, we propose a novel ALPR approach, termed VSNet. Specifically, VSNet includes two CNNs, i.e., VertexNet for license plate detection and SCR-Net for license plate recognition, integrated in a resampling-based cascaded manner. In VertexNet, we propose an efficient integration block to extract the spatial features of license plates. With vertex supervisory information, we propose a vertex-estimation branch in VertexNet such that license plates can be rectified as the input images of SCR-Net. In SCR-Net, we introduce a horizontal encoding technique for left-to-right feature extraction and propose a weight-sharing classifier for character recognition. Experimental results show that the proposed VSNet outperforms state-of-the-art methods by more than 50% relative improvement on error rate, achieving > 99% recognition accuracy on CCPD and AOLP datasets with 149 FPS inference speed. Moreover, our method illustrates an outstanding generalization capability when evaluated on the unseen PKUData and CLPD datasets.

## Article

Yi Wang, Zhen-Peng Bian, Yunhao Zhou, Lap-Pui Chau*. "Rethinking and designing a high-performing automatic license plate recognition approach." IEEE TITS 2021.

[Article](https://ieeexplore.ieee.org/abstract/document/9457131){: .btn--research} [Preprint](https://arxiv.org/abs/2011.14936){: .btn--research}
