# Image Super Resolution Project  

## Overview  
This repository contains implementations of various deep learning models for image super-resolution (SR), a computer vision task that aims to increase the resolution of images while preserving and enhancing their quality. The project includes implementations of several state-of-the-art SR models along with documentation and presentation materials.  

## Contents  

### Notebooks  
- **`EDSR.ipynb`**: Implementation of Enhanced Deep Super-Resolution Network (EDSR), a high-performance SR model that won the NTIRE 2017 Super-Resolution Challenge.  
- **`FSRCNN.ipynb`**: Implementation of Fast Super-Resolution Convolutional Neural Network (FSRCNN), a lightweight and efficient SR model designed for real-time performance.  
- **`SRCNN.ipynb`**: Implementation of Super-Resolution Convolutional Neural Network (SRCNN), one of the pioneering deep learning approaches for image super-resolution.  

### Documentation  
- **`Image Super Resolution Documentation.pdf`**: Detailed technical documentation covering the theory, implementation details, and experimental results.  
- **`Image Super Resolution Presentation.pptx`**: Presentation slides summarizing the project's objectives, methodologies, and key findings.  

### Usage  
1. Open any notebook (e.g., `EDSR.ipynb`) to explore the implementations.  
2. Follow the in-notebook instructions to train models or run super-resolution on images.  

## Results  
Sample results comparing PSNR/SSIM metrics and visual outputs on benchmark datasets (e.g., Set5, Set14).  

| Model   | PSNR (dB) | SSIM   |  
|---------|-----------|--------|  
| SRCNN   | 30.41     | 0.862  |  
| FSRCNN  | 30.72     | 0.865  |  
| EDSR    | 32.46     | 0.896  |  


## References  
- [EDSR Paper](https://arxiv.org/abs/1707.02921)  
- [FSRCNN Paper](https://arxiv.org/abs/1608.00367)  
- [SRCNN Paper](https://arxiv.org/abs/1501.00092)  
