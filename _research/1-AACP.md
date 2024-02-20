---
title: "Image Restoration in Complex Underwater Environments, IEEE TCAS-I, 2018"
layout: single-portfolio
excerpt: "<img src='/images/research/AACP.png' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "research/AACP.png"
---

![](/images/research/AACP.png)

Underwater imaging is an important topic in maritime research. Due to the existence of dust-like particles in water medium, underwater images are vulnerable to the effect of low contrast and color cast. In this paper, we propose a novel underwater image restoration method based on a non-local prior, namely adaptive attenuation-curve prior. This prior relies on the statistical distribution of pixel values. That is, all pixel values of a clear image can be partitioned into several hundred distinct clusters in RGB space, and the pixel values in each cluster will be distributed on a curve with a power function form after attenuated by water in varying degrees. Specifically, we can estimate the transmission for each pixel according to its distribution on the curves. Then, we estimate the attenuation factor to compensate for the transmission. To prevent over saturation and reduce the noise of the recovered images, we propose the saturation constraints to adjust the transmission of the three color channels. Qualitative and quantitative results demonstrate that our proposed method can achieve better performance, compared with state-of-the-art approaches. Moreover, our proposed method can further be extended to restore other kinds of degraded images, such as hazy images.

## Article

[Article](https://ieeexplore.ieee.org/abstract/document/8049307){: .btn--research} [Supplemental Information](https://drive.google.com/file/d/1KTdPS3Ih9_NOmHHA9QEZNn92lrvIS6rc/view?usp=sharing){: .btn--research} [Github Page](https://github.com/WangyiNTU/Underwater-Image-Restoration-AACP){: .btn--research}
