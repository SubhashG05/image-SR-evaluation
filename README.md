# Image Super-Resolution (SR) Model Evaluation

## Problem Statement

Image Super-Resolution (SR) is a critical image processing technique aimed at improving the resolution of low-resolution images to generate high-resolution images. This technique is essential in various applications, including medical imaging, forensic analysis, satellite imagery, and more. 

![Model Flow](Aim%20of%20the%20Project.PNG)

Despite the importance of SR, existing techniques still face several limitations:

- **Handling Unknown Degradation** 
- **Generalization Across Domains** 
- **Recovering Fine Details** 

Traditional approaches like interpolation and reconstruction-based methods often produce subpar results, prompting the use of deep learning models for SR. However, deep learning models come with their own set of issues, such as:

- **Computational Complexity** 
- **Performance Drop on Real-World Data** 
- **Dependency on Fixed Scaling Factors** 

## Research Objective

![Model Flow](Research%20Framework.PNG)

This research aims to conduct a comprehensive comparative analysis of three popular deep learning-based Super-Resolution models:

- **Super-Resolution Convolutional Neural Networks (SRCNN)**
- **SwinIR**
- **Real-ESRGAN**

The models are evaluated across multiple image domains, including Animals, Cars, Faces, Humans, Landscapes, and Ships, using different scaling factors (x2, x3, x4). 

## Evaluation Metrics

To provide a thorough evaluation, we employ various metrics, including:

- **Peak Signal-to-Noise Ratio (PSNR)**
- **Structural Similarity Index (SSIM)**
- **Feature Similarity Index (FSIM)**
- **Learned Perceptual Image Patch Similarity (LPIPS)**
- **Objective Difference Image (ODI) Score**
- **Tenengrad Sharpness**
- **Laplacian Variance**

## Proposed Approach

Our approach focuses on evaluating the performance of deep-learning SR models across different domains and scales to understand their strengths and limitations better. This comparative analysis will help identify which models are more efficient, robust, and suitable for real-world scenarios.
