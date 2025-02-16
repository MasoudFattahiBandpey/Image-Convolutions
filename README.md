# Image Convolutions - JupyterLab

## Overview
This repository contains a Jupyter Notebook exploring image convolutions and their applications in computer vision. The lab covers fundamental concepts of convolutional operations, including edge detection and feature extraction using kernels like Prewitt and Sobel operators.

## Objectives
By the end of this lab, you will be able to:
- Understand how convolution works on images
- Apply various kernels for feature extraction
- Implement edge and corner detection techniques

## Table of Contents
- [Setup](#setup)
- [Background](#background)
- [Exercises](#exercises)
  - Implementing Edge Detection
  - Implementing Corner/Blob Detection
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributors](#contributors)

## Setup
To run this lab, you need the following Python libraries:
```bash
pip install numpy matplotlib tensorflow opencv-python pillow
```

## Background
Convolutional operations allow computers to detect features in images using mathematical filters. This lab demonstrates how convolutions help in tasks such as:
- Edge detection using Prewitt and Sobel operators
- Feature enhancement with Difference of Gaussians (DoG)

## Exercises
### 1. Implementing Edge Detection
- Applying Prewitt and Sobel operators to identify edges in images

### 2. Implementing Corner/Blob Detection
- Using Difference of Gaussians (DoG) for feature extraction

## Requirements
Ensure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- Pillow

## Usage
Clone the repository and open the Jupyter Notebook:
```bash
git clone https://github.com/yourusername/image-convolutions.git
cd image-convolutions
jupyter notebook
```
Run the notebook cells sequentially to explore convolution techniques in image processing.

## Contributors
- **Richard Ye** - Original author
- **Cindy Huang** - Reviewer

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---
Feel free to modify and experiment with different kernels to see their effects on images! 🚀
