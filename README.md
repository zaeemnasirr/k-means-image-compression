# K-Means Image Compression

## 📌 Project Overview

This project applies **K-Means Clustering** for image compression through color quantization.

Each pixel in an image is treated as a three-dimensional RGB data point.  
K-Means clustering is then used to reduce the number of colors in the image by replacing each pixel with the nearest cluster centroid color.

The algorithm was implemented from scratch and tested on two simple colored images: a sunset image and a fruit image.

---

## 🎯 Objective

The main objectives of this project are:

- Implement K-Means clustering from scratch
- Treat image pixels as RGB data points
- Compress images using color quantization
- Test different K values
- Compare image quality as K increases
- Analyze reconstruction error using Mean Squared Error

---

## 🧠 Machine Learning Concept Used

- Unsupervised Learning
- K-Means Clustering
- Image Compression
- Color Quantization
- RGB Pixel Clustering
- Reconstruction Error
- Mean Squared Error

---

## ⚙️ Methodology

The K-Means algorithm follows these steps:

1. Initialize cluster centroids
2. Assign each pixel to the nearest centroid
3. Recompute centroids using cluster means
4. Repeat until convergence
5. Replace each pixel with the RGB value of its assigned centroid

The project tested the following K values:

```text
K = 2, 3, 5, 10, 15, 20
