<div align="center"> 
<img src="Images/image1.png" width="400" height="350" alt="Celebration"/>    
   
# Awesome 3D Gaussian Splatting for Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
   
 


This repo contains a curative list of **3D Gaussian Splatting papers related to the Low-Level Vision (LLV) domain**, focusing on a range of fundamental tasks in 3D image processing and enhancement. Key areas include:  Image Denoising; Low-light Image Enhancement; Image De-raining; Image Dehazing; Image Deblurring
Super-resolution Reconstruction; Image Inpainting...

#### Please feel free to send me [pull requests](https://github.com/moriyaya/awesome-3dgs-for-low-level-vision) or [email](mailto:luguoxinxin@163.com) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!
<div align="left">   
  
---

## Overview

  - [3DGS LLV Model](#3dgs-general-model)
    - [Image Denoising](#Image-Denoising)
    - [Underwater Image Enhancement](#Underwater-Image-Enhancement)
    - [Low-light Image Enhancement](#Low-light-Image-Enhancement)
    - [Image Deblurring](#Image-Deblurring)
    - [Super-resolution Reconstruction](#Super-resolution-Reconstruction)
    - [Image De-raining](#Image-De-raining)
    - [Image Fusion](#Image-Fusion)


  - [Acknowledgment](#Acknowledgment)

---
 




## 3DGS LLV Model
---
### Image Denoising
* Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting, **ECCV, 2024**. [[Paper](https://arxiv.org/pdf/2312.04820)] [[Code](https://github.com/yangxiaofeng/LODS)]
* GaussianDiffusion: 3D Gaussian Splatting for Denoising Diffusion Probabilistic Models with Structured Noise, *arXiv*. [[Paper](https://arxiv.org/pdf/2311.11221.pdf)] [[Website](https://arxiv.org/abs/2311.11221)]
---
---
### Underwater Image Enhancement
* SeaSplat: Representing Underwater Scenes with 3D Gaussian Splatting and a Physically Grounded Image Formation Model, *arXiv*. [[Paper](https://arxiv.org/pdf/2409.17345)]
* UW-GS: Distractor-Aware 3D Gaussian Splatting for Enhanced Underwater Scene Reconstruction, *arXiv*. [[Paper](https://arxiv.org/pdf/2410.01517)]
* WaterSplatting: Fast Underwater 3D Scene Reconstruction Using Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2408.08206.pdf)] [[Website](https://water-splatting.github.io/)]
---
---
### Low-light Image Enhancement
* DarkGS: Learning Neural Illumination and 3D Gaussians Relighting for Robotic Exploration in the Dark, *arXiv*. [[Paper](https://arxiv.org/abs/2403.10814.pdf)]  [[Website](https://github.com/tyz1030/darkgs)]
* Gaussian in the Dark: Real-Time View Synthesis From Inconsistent Dark Images Using Gaussian Splatting, **Pacific Graphics, 2024**. [[Paper](https://arxiv.org/pdf/2408.09130.pdf)] [[Code](https://github.com/yec22/Gaussian-DK)]
* Lighting Every Darkness with 3DGS: Fast Training and Real-Time Rendering for HDR View Synthesis, **CVPR, 2024**. [[Paper](https://arxiv.org/abs/2406.06216.pdf)] [[Code](https://github.com/Srameo/LE3D)] [[Website](https://srameo.github.io/projects/le3d/)]
---
---
### Image Deblurring
* Deblur-GS: 3D Gaussian Splatting from Camera Motion Blurred Images, **I3D, 2024**. [[Paper](https://chaphlagical.icu/Deblur-GS/static/paper/Deblur_GS_author_version.pdf)]  [[Code](https://github.com/Chaphlagical/Deblur-GS)]
* Deblurring 3D Gaussian Splatting, **ECCV, 2024**. [[Website](https://benhenryl.github.io/Deblurring-3D-Gaussian-Splatting/)]  [[Code](https://github.com/benhenryL/Deblurring-3D-Gaussian-Splatting)]
---
---
### Super-resolution Reconstruction
* GaussianSR: 3D Gaussian Super-Resolution with 2D Diffusion Priors, *arXiv*. [[Paper](https://arxiv.org/abs/2406.10111.pdf)] [[Website](https://chchnii.github.io/GaussianSR/)]
* SRGS: Super-Resolution 3D Gaussian Splatting, **ACM MM, 2024**. [[Paper](https://arxiv.org/abs/2404.10318.pdf)] [[Code](https://github.com/XiangFeng66/SRGS)]
* GaussianSR: High Fidelity 2D Gaussian Splatting for Arbitrary-Scale Image Super-Resolution, *arXiv*. [[Paper](https://arxiv.org/abs/2407.18046.pdf)] 
* LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation, *arXiv*. [[Paper](https://arxiv.org/pdf/2402.05054.pdf)] [[Website](https://me.kiui.moe/lgm/)] [[Code](https://github.com/3DTopia/LGM)]
* FlashGS: Efficient 3D Gaussian Splatting for Large-scale and High-resolution Rendering, *arXiv*. [[Paper](https://arxiv.org/pdf/2408.07967.pdf)]
* FastSR-NeRF: Improving NeRF Efficiency on Consumer Devices With a Simple Super-Resolution Pipeline, **WACV, 2024**. [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Lin_FastSR-NeRF_Improving_NeRF_Efficiency_on_Consumer_Devices_With_a_Simple_WACV_2024_paper.pdf)]
*  4K4D: Real-Time 4D View Synthesis at 4K Resolution. [[Paper](https://drive.google.com/file/d/1Y-C6ASIB8ofvcZkyZ_Vp-a2TtbiPw1Yx/view?usp=sharing)] [[Website](https://zju3dv.github.io/4k4d/) | [Code (Inference)](https://github.com/zju3dv/4K4D)]]
---
---
### Image De-raining
* DeRainGS: Gaussian Splatting for Enhanced Scene Reconstruction in Rainy Environments, *arXiv*. [[Paper](https://arxiv.org/pdf/2408.11540)]
---
---
### Image Fusion
* Thermal3D-GS: Physics-induced 3D Gaussians for Thermal Infrared Novel-view Synthesis, **ECCV, 2024**. [[Paper](https://arxiv.org/abs/2409.08042)]  [[Code](https://github.com/mzzcdf/Thermal3DGS)]
* ThermalGaussian: Thermal 3D Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2409.07200)]
*  4K4D: Real-Time 4D View Synthesis at 4K Resolution. [[Paper](https://drive.google.com/file/d/1Y-C6ASIB8ofvcZkyZ_Vp-a2TtbiPw1Yx/view?usp=sharing)] [[Website](https://zju3dv.github.io/4k4d/) | [Code (Inference)](https://github.com/zju3dv/4K4D)]]
---

 

## Acknowledgment


The template of this website is inspired by [awesome-3dgs-for-robotics](https://github.com/dtc111111/awesome-3dgs-for-robotics), and we appreciate their contribution.
