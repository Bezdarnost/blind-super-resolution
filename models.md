<details>
<summary>DiffPIR: Denoising Diffusion Models for Plug-and-Play Image Restoration (05.2023)</summary>

---

**Data of Introduction:**

- May 15, 2023

**Conference/Publication:**

- CVPR workshop NTIRE 2023

**Authors:**

- Yuanzhi Zhu, Kai Zhang, Jingyun Liang, Jiezhang Cao, Bihan Wen, Radu Timofte, Luc Van Gool

**Abstract/Description:**

- The paper introduces DiffPIR, a method that integrates traditional plug-and-play image restoration into the diffusion sampling framework. While most existing methods focus on discriminative Gaussian denoisers, this work explores the potential of diffusion models as a generative denoiser prior for plug-and-play image restoration. The proposed approach demonstrates state-of-the-art performance on various image restoration tasks, including super-resolution, image deblurring, and inpainting.

**Main Concepts:**

- Utilization of any off-the-shelf denoiser as an implicit image prior.
- Exploration of diffusion models as a generative denoiser prior.
- Integration of traditional plug-and-play methods into the diffusion sampling framework.

**Architecture & Methods:**

- DiffPIR: A method that combines plug-and-play image restoration with diffusion models.
- Uses diffusion models as generative denoisers, offering a potential improvement over traditional Gaussian denoisers.

**Training Details:**

- Specific training details are not provided in the summary, but the paper likely delves deeper into the training process and parameters.

**Metrics:**

- Metrics related to reconstruction faithfulness and perceptual quality were used, though specific metric names are not mentioned in the summary.

**Datasets:**

- Training: Not explicitly mentioned in the summary.
- Testing: FFHQ and ImageNet datasets were used for evaluation.

**Results & Achievements:**

- DiffPIR achieves state-of-the-art performance on various image restoration tasks.
- Demonstrates superior quality in terms of reconstruction faithfulness and perceptual quality, requiring no more than 100 Neural Function Evaluations (NFEs).

**Code/Implementation:**

- The source code is available at [DiffPIR GitHub Repository](https://github.com/yuanzhi-zhu/DiffPIR).

**References:**

- [paper](https://arxiv.org/pdf/2305.08995.pdf)
- [github](https://github.com/yuanzhi-zhu/DiffPIR)

```
@inproceedings{zhu2023denoising, % DiffPIR
      title={Denoising Diffusion Models for Plug-and-Play Image Restoration},
      author={Yuanzhi Zhu and Kai Zhang and Jingyun Liang and Jiezhang Cao and Bihan Wen and Radu Timofte and Luc Van Gool},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition Workshops (NTIRE)},
      year={2023}
}
```

---
  
</details>

<details>
<summary>SCUNet: Practical Blind Denoising via Swin-Conv-UNet and Data Synthesis (03.2022)</summary>

---

**Date of Introduction:**

- March 28, 2022

**Conference/Publication:**

- ArXiv (preprint)

**Authors:**

- Kai Zhang, Yawei Li, Jingyun Liang, Jiezhang Cao, Yulun Zhang, Hao Tang, Radu Timofte, Luc Van Gool

**Abstract/Description:**

- The paper addresses the challenge of blind image denoising, where most existing methods rely on simple noise assumptions. The authors propose a new approach, DiffPIR, that integrates traditional plug-and-play image restoration into the diffusion sampling framework. The proposed method, Swin-Conv-UNet, combines the strengths of the Swin Transformer and convolutional networks. Additionally, a new noise degradation model is introduced, which considers various types of noise and incorporates strategies like random shuffle and double degradation. The method achieves state-of-the-art performance on various denoising tasks.

**Main Concepts:**

- Challenges with existing denoising methods and their reliance on simple noise assumptions.
- Introduction of Swin-Conv-UNet, which combines local modeling ability of convolutional layers with non-local modeling of Swin Transformer.
- Design of a practical noise degradation model that considers various noise types and incorporates strategies for more realistic training.

**Architecture & Methods:**

- Swin-Conv-UNet (SCUNet): A network that integrates Swin Transformer blocks with convolutional layers. It's designed to capture both local and non-local image features effectively.
- Noise Degradation Model: A model that simulates various types of noise, including Gaussian, Poisson, speckle, JPEG compression, and camera sensor noises. It also uses strategies like random shuffle and double degradation.

**Training Details:**

- The paper emphasizes the importance of a realistic noise model for training. While specific training details are not provided in the summary, the paper likely delves deeper into the training process and parameters.

**Metrics:**

- The paper likely uses standard denoising metrics, though specific metric names are not mentioned in the summary.

**Datasets:**

- The paper mentions the use of various noise types for training, suggesting the use of diverse datasets. Specific dataset names are not provided in the summary.

**Results & Achievements:**

- The proposed Swin-Conv-UNet achieves state-of-the-art performance on denoising tasks.
- The noise degradation model improves the practicability of the denoising model for real images.

**Code/Implementation:**

- The source code is available at [SCUNet GitHub Repository](https://github.com/cszn/SCUNet).

**References:**

- [paper](https://arxiv.org/pdf/2203.13278.pdf)
- [github](https://github.com/cszn/SCUNet)

```
@article{zhang2022practical,
title={Practical Blind Denoising via Swin-Conv-UNet and Data Synthesis},
author={Zhang, Kai and Li, Yawei and Liang, Jingyun and Cao, Jiezhang and Zhang, Yulun and Tang, Hao and Timofte, Radu and Van Gool, Luc},
journal={arXiv preprint},
year={2022}
}
```

---
      
</details>

