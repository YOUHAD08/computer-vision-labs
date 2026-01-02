# 🎓 Computer Vision Labs

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-yellow.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A comprehensive collection of computer vision laboratory exercises covering fundamental to advanced techniques in image processing, machine learning, and deep learning.

---

## 📚 Overview

This repository contains practical implementations and solutions for computer vision assignments, organized into separate lab modules. Each lab focuses on specific computer vision techniques, from basic image processing operations to machine learning classification tasks.

> **Academic Context:** These labs are part of a Computer Vision course, designed to provide hands-on experience with industry-standard tools and methodologies.

---

## 📁 Repository Structure

```
COMPUTER-VISION-LABS/
│
├── lab-1/                          # Image Processing Fundamentals
│   ├── images/                     # Sample images for exercises
│   ├── 01_grayscale_motion_detection.ipynb
│   ├── 02_traffic_light_color_spaces.ipynb
│   ├── 03_drawing_football_annotations.ipynb
│   ├── 04_image_transformations.ipynb
│   ├── 05_resizing_interpolation_cropping.ipynb
│   ├── 06_thresholding_histograms.ipynb
│   ├── 07_gamma_correction_enhancement.ipynb
│   ├── 08_convolutions_blurring_sharpening.ipynb
│   ├── 09_histogram_specification.ipynb
│   ├── Assignment 1.pdf
│   └── README.md
│
├── lab-2/                          # Machine Learning Classification
│   ├── KNN_CIFAR10.ipynb          # K-Nearest Neighbors implementation
│   └── Assignment 2.pdf
│
├── cv_env/                         # Python virtual environment
├── .gitignore
└── requirements.txt
```

---

## 🔬 Lab Modules

### Lab 1: Image Processing Fundamentals

Core OpenCV techniques covering color spaces (RGB, HSV, YCrCb), geometric transformations, histogram analysis, and advanced filtering methods.

#### Highlights:

- ✅ Motion detection optimization (3x faster with grayscale)
- ✅ Traffic light detection using HSV color space (95%+ accuracy)
- ✅ Noise reduction comparison (Median vs Gaussian vs NL-Means)
- ✅ Histogram-based image style transfer

[**→ View Lab 1 Details**](./lab-1/README.md)

---

### Lab 2: K-Nearest Neighbors Classification

KNN implementation on CIFAR-10 dataset with cross-validation for optimal hyperparameter selection.

#### Key Features:

- ✅ 5-fold cross-validation across k values [1-100]
- ✅ Systematic hyperparameter optimization
- ✅ Test accuracy: ~34% on CIFAR-10 subset
- ✅ Performance visualization with error bars

---

## 🛠️ Technologies Used

| Category                | Tools & Libraries              |
| ----------------------- | ------------------------------ |
| **Core**                | Python 3.8+                    |
| **Image Processing**    | OpenCV, scikit-image, PIL      |
| **Machine Learning**    | scikit-learn, TensorFlow/Keras |
| **Numerical Computing** | NumPy, SciPy                   |
| **Visualization**       | Matplotlib, Seaborn            |
| **Development**         | Jupyter Notebook, VS Code      |

---

## 🎯 Future Labs (Coming Soon)

- **Lab 3:** Feature Detection & Matching (SIFT, ORB, Harris corners)
- **Lab 4:** Object Detection (YOLO, Haar Cascades)
- **Lab 5:** Deep Learning for Vision (CNNs, Transfer Learning)
- **Lab 6:** Video Processing & Tracking
- **Lab 7:** Semantic Segmentation
- **Lab 8:** Generative Models (GANs, VAEs)
