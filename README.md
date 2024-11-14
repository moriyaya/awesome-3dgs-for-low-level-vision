<div align="center"> 
<img src="Images/image1.jpg" width="300" height="250" alt="Celebration"/>    
   
# Awesome 3D Gaussian Splatting for Low-Level Vision  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
   
 


This repo contains a curative list of **3D Gaussian Splatting papers related to the Low-Level Vision (LLV) domain**, specifically focusing on 3D Gaussian Splatting applications in challenging environments and low-quality images. This includes noisy images, underwater scenes, night/low-light conditions, blurry images, low-resolution images, rainy scenes, and infrared/visible light images.

#### Please feel free to send me [pull requests](https://github.com/moriyaya/awesome-3dgs-for-low-level-vision) or [email](mailto:luguoxinxin@163.com) to add papers! <br>

If you find this repository useful, please consider STARing this list. Feel free to share this list with others!
<div align="left">   
  
---

## Overview

  - [3DGS LLV Model](#3dgs-general-model)
    - [Noisy Images](#Image-Denoising)
    - [Underwater Scenes](#Underwater-Image-Enhancement)
    - [Night/Low-light Conditions](#Low-light-Image-Enhancement)
    - [Blurry Images](#Image-Deblurring)
    - [Super-resolution Reconstruction](#Super-resolution-Reconstruction)
    - [Rainy Scenes](#Image-De-raining)
    - [Foggy Scenes](#Image-De-haze)
    - [Image High Dynamic Range](#High-Dynamic-Range)        
    - [Thermal Infrared](#Thermal-Infrared)


  - [Acknowledgment](#Acknowledgment)

---
 




## 3DGS LLV Model

### Noisy Images
* Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting, **ECCV, 2024**. [[Paper](https://arxiv.org/pdf/2312.04820)] [[Code](https://github.com/yangxiaofeng/LODS)]
* GaussianDiffusion: 3D Gaussian Splatting for Denoising Diffusion Probabilistic Models with Structured Noise, *arXiv*. [[Paper](https://arxiv.org/pdf/2311.11221.pdf)] [[Website](https://arxiv.org/abs/2311.11221)]
* DN-4DGS: Denoised Deformable Network with Temporal-Spatial Aggregation for Dynamic Scene Rendering, **NeurIPS, 2024**. [[Paper](https://arxiv.org/abs/2410.13607)] [[Code](https://github.com/peoplelu/DN-4DGS)]
* Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2312.04820)]
* GaussianDiffusion: 3D Gaussian Splatting for Denoising Diffusion Probabilistic Models with Structured Noise, *arXiv*. [[Paper](https://arxiv.org/abs/2311.11221)]

### Underwater Scenes
* SeaSplat: Representing Underwater Scenes with 3D Gaussian Splatting and a Physically Grounded Image Formation Model, *arXiv*. [[Paper](https://arxiv.org/pdf/2409.17345)][[Website](https://seasplat.github.io)]
* UW-GS: Distractor-Aware 3D Gaussian Splatting for Enhanced Underwater Scene Reconstruction, *arXiv*. [[Paper](https://arxiv.org/pdf/2410.01517)]
* WaterSplatting: Fast Underwater 3D Scene Reconstruction Using Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2408.08206.pdf)] [[Website](https://water-splatting.github.io/)]
* Aquatic-GS: A Hybrid 3D Representation for Underwater Scenes, *arXiv*. [[Paper](https://arxiv.org/abs/2411.00239)] [[Website](https://aquaticgs.github.io/)]
* RecGS: Removing Water Caustic with Recurrent Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2407.10318)]

### Night/Low-light Conditions
* DarkGS: Learning Neural Illumination and 3D Gaussians Relighting for Robotic Exploration in the Dark, *arXiv*. [[Paper](https://arxiv.org/abs/2403.10814.pdf)]  [[Website](https://github.com/tyz1030/darkgs)]
* Gaussian in the Dark: Real-Time View Synthesis From Inconsistent Dark Images Using Gaussian Splatting, **Pacific Graphics, 2024**. [[Paper](https://arxiv.org/pdf/2408.09130.pdf)] [[Code](https://github.com/yec22/Gaussian-DK)]
* Lighting Every Darkness with 3DGS: Fast Training and Real-Time Rendering for HDR View Synthesis, **CVPR, 2024**. [[Paper](https://arxiv.org/abs/2406.06216.pdf)] [[Code](https://github.com/Srameo/LE3D)] [[Website](https://srameo.github.io/projects/le3d/)]
* From Chaos to Clarity: 3DGS in the Dark, *arXiv*. [[Paper](https://arxiv.org/abs/2406.08300)][[Website](https://lizhihao6.github.io/Raw3DGS)]

### Blurry Images
* Deblur-GS: 3D Gaussian Splatting from Camera Motion Blurred Images, **I3D, 2024**. [[Paper](https://chaphlagical.icu/Deblur-GS/static/paper/Deblur_GS_author_version.pdf)]  [[Code](https://github.com/Chaphlagical/Deblur-GS)]
* Deblurring 3D Gaussian Splatting, **ECCV, 2024**. [[Website](https://benhenryl.github.io/Deblurring-3D-Gaussian-Splatting/)]  [[Code](https://github.com/benhenryL/Deblurring-3D-Gaussian-Splatting)]
* EvaGaussians: Event Stream Assisted Gaussian Splatting from Blurry Images, *arXiv*. [[Paper](https://arxiv.org/abs/2405.20224)][[Website](https://drexubery.github.io/EvaGaussians/)]
* BAD-Gaussians: Bundle Adjusted Deblur Gaussian Splatting, **ECCV, 2024**. [[Paper](https://arxiv.org/abs/2403.11831)][[Website](https://lingzhezhao.github.io/BAD-Gaussians/)]
* BAGS: Blur Agnostic Gaussian Splatting through Multi-Scale Kernel Modeling, **ECCV, 2024**. [[Paper](https://arxiv.org/pdf/2403.04926.pdf)][[Website](https://nwang43jhu.github.io/BAGS/)]
* Gaussian Splatting on the Move: Blur and Rolling Shutter Compensation for Natural Camera Motion, **ECCV, 2024**. [[Paper](https://arxiv.org/pdf/2403.13327)][[Website](https://spectacularai.github.io/3dgs-deblur/)]
* DeblurGS: Gaussian Splatting for Camera Motion Blur, *arXiv*. [[Code](https://github.com/taekkii/deblurgs)]
* Robust Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2404.04211)]
* CRiM-GS: Continuous Rigid Motion-Aware Gaussian Splatting from Motion Blur Images, *arXiv*. [[Paper](https://arxiv.org/abs/2407.03923)][[Website](https://jho-yonsei.github.io/CRiM-Gaussian/)]


### Super-resolution Reconstruction
* GaussianSR: 3D Gaussian Super-Resolution with 2D Diffusion Priors, *arXiv*. [[Paper](https://arxiv.org/abs/2406.10111.pdf)] [[Website](https://chchnii.github.io/GaussianSR/)]
* SRGS: Super-Resolution 3D Gaussian Splatting, **ACM MM, 2024**. [[Paper](https://arxiv.org/abs/2404.10318.pdf)] [[Code](https://github.com/XiangFeng66/SRGS)]
* GaussianSR: High Fidelity 2D Gaussian Splatting for Arbitrary-Scale Image Super-Resolution, *arXiv*. [[Paper](https://arxiv.org/abs/2407.18046.pdf)] 
* LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation, *arXiv*. [[Paper](https://arxiv.org/pdf/2402.05054.pdf)] [[Website](https://me.kiui.moe/lgm/)] [[Code](https://github.com/3DTopia/LGM)]
* FlashGS: Efficient 3D Gaussian Splatting for Large-scale and High-resolution Rendering, *arXiv*. [[Paper](https://arxiv.org/pdf/2408.07967.pdf)]
*  4K4D: Real-Time 4D View Synthesis at 4K Resolution. [[Paper](https://drive.google.com/file/d/1Y-C6ASIB8ofvcZkyZ_Vp-a2TtbiPw1Yx/view?usp=sharing)] [[Website](https://zju3dv.github.io/4k4d/) | [Code (Inference)](https://github.com/zju3dv/4K4D)]]
* FastSR-NeRF: Improving NeRF Efficiency on Consumer Devices With a Simple Super-Resolution Pipeline, **WACV, 2024**. [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Lin_FastSR-NeRF_Improving_NeRF_Efficiency_on_Consumer_Devices_With_a_Simple_WACV_2024_paper.pdf)]
* SuperGS: Super-Resolution 3D Gaussian Splatting via Latent Feature Field and Gradient-guided Splitting, *arXiv*. [[Paper](https://arxiv.org/abs/2410.02571)]
* SuperGaussian: Repurposing Video Models for 3D Super Resolution, **ECCV, 2024**. [[Paper](https://arxiv.org/abs/2406.00609)][[Website](https://supergaussian.github.io/)]
* Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models , **ACM MM, 2024**. [[Paper](https://arxiv.org/abs/2409.07452)][[Website](https://github.com/yanghb22-fdu/Hi3D-Official)]
* Deceptive-NeRF/3DGS: Diffusion-Generated Pseudo-Observations for High-Quality Sparse-View Reconstruction, **ECCV, 2024**. [[Paper](https://arxiv.org/abs/2305.15171)]
* On Scaling Up 3D Gaussian Splatting Training, *arXiv*. [[Paper](https://arxiv.org/abs/2406.18533)] [[Website](https://daohanlu.github.io/scaling-up-3dgs/)]
* 4K4DGen: Panoramic 4D Generation at 4K Resolution, *arXiv*. [[Paper](https://arxiv.org/abs/2406.13527)] 

### Rainy Scenes
* DeRainGS: Gaussian Splatting for Enhanced Scene Reconstruction in Rainy Environments, *arXiv*. [[Paper](https://arxiv.org/pdf/2408.11540)]
* RainyScape: Unsupervised Rainy Scene Reconstruction using Decoupled Neural Rendering, *arXiv*. [[Paper](https://arxiv.org/abs/2404.11401)]

### Foggy Scenes
* DehazeNeRF: Multiple Image Haze Removal and 3D Shape Reconstruction using Neural Radiance Fields, **3DV, 2024**. [[Paper](https://arxiv.org/abs/2303.11364)] [[Website](https://www.computationalimaging.org/publications/dehazenerf/)]
* Reliable Image Dehazing by NeRF, *arXiv*. [[Paper](https://arxiv.org/abs/2303.09153)]

### High Dynamic Range
* HDRGS: High Dynamic Range Gaussian Splatting,  *arXiv*. [[Paper](https://arxiv.org/abs/2408.06543)] 
* HDRSplat: Gaussian Splatting for High Dynamic Range 3D Scene Reconstruction from Raw Images, *arXiv*. [[Paper](https://arxiv.org/abs/2407.16503)]
* HDR-GS: Efficient High Dynamic Range Novel View Synthesis at 1000x Speed via Gaussian Splatting, **NeurIPS, 2024**. [[Paper](https://arxiv.org/abs/2405.15125)] 

### Thermal Infrared 
* Thermal3D-GS: Physics-induced 3D Gaussians for Thermal Infrared Novel-view Synthesis, **ECCV, 2024**. [[Paper](https://arxiv.org/abs/2409.08042)]  [[Code](https://github.com/mzzcdf/Thermal3DGS)]
* ThermalGaussian: Thermal 3D Gaussian Splatting, *arXiv*. [[Paper](https://arxiv.org/abs/2409.07200)]
---

 

## Acknowledgment


The template of this website is crafted with reference to [awesome-3dgs-for-robotics](https://github.com/dtc111111/awesome-3dgs-for-robotics), and we appreciate their contribution.
