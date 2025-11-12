# 🩺 Medical Image Processing & Analysis

**Academic Project (M.Eng) | Nov 2025 – Dec 2025 (In Progress)**

This project focuses on implementing fundamental computer vision and processing techniques for medical imaging, with a specialization in the **DICOM** and **NIFTI** file standards.

## 🎯 Project Goal

To build a software toolkit capable of reading, processing, and analyzing medical images to perform key tasks like segmentation, filtering, and registration.

## 🛠️ Core Concepts & Techniques

* **Image Processing Fundamentals:**
    * Filtering and convolution (mean, median, custom kernels)
    * Frequency domain processing (Fourier Transform)
    * Morphological operations (erosion, dilation, opening, closing)
    * Edge and feature detection (Sobel, Canny, Hough Transform)
    * Histogram analysis (stretching, equalization)

* **Medical Data Handling & Segmentation:**
    * Parsing and visualizing 3D/4D data: DICOM (`pydicom`) and NIfTI (`nibabel`)
    * 3D volume visualization (axial, coronal, sagittal) and Hounsfield Unit (HU) windowing
    * Segmentation methods: Otsu's thresholding, Watershed, Random Walker, texture-based (LBP)
    * Performance evaluation: Dice (DSC), Jaccard (IoU), and Hausdorff Distance

* **Image Registration:**
    * Spatial alignment theory (rigid, affine, and deformable transforms)
    * Multi-modal registration (CT to MRI) using similarity metrics like Mutual Information (MI)
    * Implementation with **ANTsPy** (Symmetric Normalization - SyN)
 

## Technology Stack

* Python
* NumPy
* Scikit-image
* Pydicom & Nibabel
* ANTsPy
* SimpleITK
* Nilearn
* Matplotlib
* Jupyter Notebook

## 🔒 Code Availability

As per ULB academic regulations, the source code for this project is not publicly available. Please contact me for a detailed discussion of the algorithms and data structures used.
