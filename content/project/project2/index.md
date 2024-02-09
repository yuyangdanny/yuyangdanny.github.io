---
title: Parallelize Image Stitching
summary: |
  <em><small style="background-color: #c5c5f7; color: #330066; padding: 5px;">C++/CUDA/OpenMP/OpenCV</small></em><br>
  <small><em>Dec 2022 – Jan 2023</em></small><br>
  Stitched a series of consecutive images to create panoramic image, accelerating the RANSAC algorithm and Homography transform using CUDA for parallel computation, achieving a <b style="color: red;">5.3x</b> speedup using a single GPU
tags:
  - Computer Vision
date: "2022-12-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Repository
    url: https://github.com/yuyangdanny/Parallelize-Image-Stitching
---
### Abstract
Image stitching has applications in projects involving 360 layouts or 3D scene reconstruction. For instance, in data collection scenarios for 360 layouts, achieving higher FPS can greatly enhance the potential for real-time scene reconstruction when combined with AI models for 3D reconstruction. Therefore, I implemented optimizations using CUDA to improve the overall computation speed of image stitching.