# Mean-Shift-K-Means-Agglomerative-Region-Growing-Global-Thresholding
## Table of Contents
- [Introduction](#introduction)
- [Project Features](#project-features)
- [Quick Preview](#quick-preview)
- [Requirements to Run](#requirements-to-run)
- [Team](#team)

### Introduction
------------------------------------------
This project covers the implementation and comparison of various image segmentation algorithms, including Mean Shift, Agglomerative Clustering, K-Means, Region Growing, Global Thresholding, and Local Thresholding. These methods are applied to image data to explore their effectiveness in different scenarios.

## Project Features
------------------------------------------
### - Mean Shift Algorithm:
- Bandwidth and mean shift vector initialization.
- Iterative mean shift computation with convergence check.
- Cluster assignment based on mode identification.
- Agglomerative Clustering:
- Pairwise distance computation and merging of closest clusters.
- Repeated merging until the desired number of clusters is achieved.


### - K-Means Clustering:
- Random initialization of centroids.
- Iterative assignment of data points to nearest centroids and centroid update.
- Convergence based on centroid position changes.


### - Region Growing:
- Region-based segmentation using seed points.
- Colorization and detection functions for labelled regions.


### - Global Thresholding:
- Otsu’s Thresholding: Automatic threshold selection to maximize between-class variance.
- Entropy Thresholding: Threshold selection based on maximum information gain.

### -Local Thresholding:
- Spectral Thresholding: Application of Otsu’s method in local regions.
- Variance Thresholding: Thresholding based on local variance.
- Double Thresholding: Segmentation into low, medium, and high-intensity regions.
- Multi-level Thresholding: Segmentation using multiple thresholds.

### Quick Preview
------------------------------------------
Here are some outputs generated from the algorithms implemented in this project:

### K-Means
![1-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/825ec4fb-efbb-44e9-bafd-8f4ea58e1f5c)

### Mean-Shift
![2-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/e6b0f67e-4073-49be-882b-b164c13410d2)

### Thresholding
![3-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/389d34ee-baa6-40f7-8528-0229d078eab9)

### Agglomerative
![4-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/8e8220b0-9248-4dcd-bcf3-d8314ce3b493)

### Region Growing
![5-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/ec0e1c23-2dde-4752-b307-aa1d4eb06bf9)

### Color Modes
![6-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/2d6a7879-6842-447e-afd8-91a3cf59aea3)

### Requirements to Run
------------------------------------------

To run the project, you need:

C++ compiler
Qt framework
OpenCV library
Run the Project

## Contributors <a name="Contributors"></a>

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Mahmoudm007" target="_black">
      <img src="https://avatars.githubusercontent.com/u/101353088?v=4" width="190px;" alt="Mahmoud M."/>
      <br />
      <sub><b>Mahmoud M. Abdelaty</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/AhmedKamalMohammedElSayed" target="_black">
      <img src="https://avatars.githubusercontent.com/u/96977876?v=4" width="190px;" alt="Ahmed Kamal"/>
      <br />
      <sub><b>Ahmed Kamal</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/amg-eng" target="_black">
      <img src="https://avatars.githubusercontent.com/u/101107538?v=4" width="190px;" alt="Amgad Atef"/>
      <br />
      <sub><b>Amgad Atef</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/MahmoudMagdy404" target="_black">
      <img src="https://avatars.githubusercontent.com/u/83336074?v=4" width="190px;" alt="Amgad Atef"/>
      <br />
      <sub><b>Mahmoud Magdy</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/mohandemadx" target="_black">
      <img src="https://avatars.githubusercontent.com/u/102548631?v=4" width="190px;" alt="Amgad Atef"/>
      <br />
      <sub><b>Mahmoud Magdy</b></sub></a>
    </td>
  </tr>
</table>
