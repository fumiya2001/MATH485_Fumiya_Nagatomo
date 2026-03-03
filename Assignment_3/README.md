# Overview

This assignment aims to understand the concept of Singular Value Decomposition (SVD) and its application in block-wise image compression.

A grayscale image is divided into non-overlapping 8×8 blocks, and SVD is applied to each block. The image is reconstructed using the top-k singular values (k = 1 to 8) to analyze the trade-off between compression ratio and image quality.

# Requirements

- Python 3.13
- numpy
- pandas
- matplotlib

# How to Run

1. Open the notebook `Assignment_3.ipynb`.
2. Run all cells from top to bottom.
3. The reconstructed images and compression results for 4×4 and 16×16 block sizes will be displayed automatically.
4. The reconstructed images for the 8×8 block size can be found in the `output` folder.
