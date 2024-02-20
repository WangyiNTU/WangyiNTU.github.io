---
title: "Image Restoration in Bitstream-Corrupted JPEG Images, CVPR, 2023"
layout: single-portfolio
excerpt: "<img src='/images/research/Two-ACIR.png' alt=''>"
collection: research
order_number: 20
header: 
  og_image: "research/Two-ACIR.png"
---

![](/images/research/Two-ACIR.png)

In this research, we study a real-world JPEG image restoration problem with bit errors on the encrypted bitstream. The bit errors bring unpredictable color casts and block shifts on decoded image contents, which cannot be resolved by existing image restoration methods mainly relying on pre-defined degradation models in the pixel domain. To address these challenges, we propose a robust JPEG decoder, followed by a two-stage compensation and alignment framework to restore bitstream-corrupted JPEG images. 

Specifically, the robust JPEG decoder adopts an error-resilient mechanism to decode the corrupted JPEG bitstream. The two-stage framework is composed of the self-compensation and alignment (SCA) stage and the guided compensation and alignment (GCA) stage. The SCA adaptively performs block-wise image color compensation and alignment based on the estimated color and block offsets via image content similarity. The GCA leverages the extracted low-resolution thumbnail from the JPEG header to guide full-resolution pixel-wise image restoration in a coarse-to-fine manner. It is achieved by a coarse-guided pix2pix network and a refine-guided bi-directional Laplacian pyramid fusion network. We conduct experiments on three benchmarks with varying degrees of bit error rates. Experimental results and ablation studies demonstrate the superiority of our proposed method.

## Article

Wenyang Liu, Yi Wang*, Kim-Hui Yap*, and Lap-Pui Chau. "Bitstream-Corrupted JPEG Images are Restorable: Two-stage Compensation and Alignment Framework for Image Restoration." CVPR 2023.

[Article](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Bitstream-Corrupted_JPEG_Images_Are_Restorable_Two-Stage_Compensation_and_Alignment_Framework_CVPR_2023_paper.pdf){: .btn--research} [Preprint](https://arxiv.org/abs/2304.06976){: .btn--research} [Supplemental Information](https://openaccess.thecvf.com/content/CVPR2023/supplemental/Liu_Bitstream-Corrupted_JPEG_Images_CVPR_2023_supplemental.pdf){: .btn--research} [GitHub Repo](https://github.com/wenyang001/Two-ACIR){: .btn--research} [Poster](){: .btn--research}
