# IMA 208 TP5: Homography Estimation

This Jupyter notebook is part of the IMA 208 course material and focuses on the estimation of homographies, an essential technique in computer vision for image alignment and stitching. The notebook is divided into two main parts, each designed to progressively introduce the concept and application of homographies.

## Prerequisites

- Basic understanding of linear algebra and computer vision.
- Python programming skills.
- Familiarity with Jupyter notebooks.

## Setup

Ensure you have a Python environment set up with the following libraries:
- `numpy`
- `matplotlib`
- `opencv-python` (for image processing functions)

## Part 1: Homography Estimation from Hand-Selected Keypoints: DLT Algorithm

This section introduces the Direct Linear Transform (DLT) algorithm for homography estimation. It guides you through selecting keypoints manually in pairs of images and using these points to estimate a homography matrix. This fundamental technique is crucial for understanding how images can be aligned based on selected correspondences.

## Part 2: Automatic Homography Estimation and Panorama Stitching

Building on the concepts from Part 1, this section delves into automatic keypoint detection and homography estimation. You'll learn how to stitch images together to create panoramas automatically, utilizing the estimated homography matrices. This part showcases practical applications of homographies in creating wide-angle views from multiple images.
