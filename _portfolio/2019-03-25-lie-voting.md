---
title: "Symmetry and Orbit Detection in Point Clouds"
excerpt: "<img src='/assets/img/projects/lie_voting.png'>"
collection: portfolio
---

![Picture](/assets/img/projects/lie_voting.png)

Symmetry and orbit are important global features for point clouds but the detection remains a huge challenge. In this project, I studied the paper: [Symmetry and Orbit Detection via Lie-Algebra Voting](http://www.geometry.caltech.edu/pubs/SADBH16.pdf). The main idea is to embedding patches into a Lie algebra $\mathfrak{sim}(d)$ with an optimal distance metric. Then RANSAC or Mean-shift is used to extract correponding structures. 

In this project, I achieved the following goals:

* Adapted the algorithm to 2D point clouds and implemented it in Python, to facilitate the visualization and parameter tuning.

* Implemented the algorithm on 3d point clouds in C++, which allows a fast computation on big point cloud.

* Studied the influence of different parameters

## Requirements

### 2D Case

* \>= Python 3
* Numpy, Sklearn, matplotlib

### 3D Case

* CGAL
* Eigen
* cpp 11+

## Source Code

[Code](https://github.com/Tong-ZHAO/Symmetry_orbit_detection) / [Report](https://github.com/Tong-ZHAO/MVA_Courses_2018/blob/master/Nuage_Points/project/report.pdf) / [Slide](https://github.com/Tong-ZHAO/MVA_Courses_2018/blob/master/Nuage_Points/project/slide.pdf)
