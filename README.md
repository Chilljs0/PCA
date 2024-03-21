# PCA
# Image Compression Using PCA and SVD

This repository contains two Jupyter notebooks using Principal Component Analysis (PCA) through eigenvalue decomposition and Singular Value Decomposition (SVD).

## Description

The project consists of two main components:

1. **PCA Image Compression**: A Jupyter notebook (`pca.ipynb`) that demonstrates how to compress grayscale images using PCA by performing eigenvalue decomposition on the image's covariance matrix.

2. **SVD Image Compression**: A Jupyter notebook (`pca_svd.ipynb`) that showcases grayscale image compression using SVD. This method decomposes the image matrix directly, without computing the covariance matrix, to achieve compression.

Both notebooks will eventually include detailed explanations of each step in the compression process, from preprocessing the image data to reconstructing the compressed images.

## Installation

To run these notebooks, you will need a Python environment with Jupyter and the following packages installed:
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
