# CCTV Low-Light Image Enhancement Project

## Overview

This project enhances low-light CCTV images using image processing techniques and performs object classification using machine learning. The system improves image visibility, segments regions of interest, extracts image features, and classifies objects into person and non-person categories.

---

## Features

- Low-light image enhancement
- ROI segmentation using Otsu's Thresholding
- Feature extraction using Histogram and GLCM
- Object classification using Random Forest
- Image quality evaluation using PSNR and SSIM

---

## Dataset

- **Source:** ExDark Dataset / Custom CCTV Images
- **Image Type:** Color images converted to grayscale
- **Purpose:** Low-light image enhancement and object classification

---

## Methodology

### Image Enhancement
- Noise Reduction
- CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Unsharp Masking
- Wavelet-based Multiresolution Enhancement

### ROI Segmentation
- Otsu's Thresholding

### Feature Extraction
- Histogram Features
- GLCM Texture Features

### Classification
- Random Forest Classifier

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Scikit-image
- Pandas
- Matplotlib

---

## Evaluation Metrics

### Image Quality
- PSNR
- SSIM

### Classification
- Accuracy
- Precision
- Recall
- F1-Score

---

## Project Structure

```
image-processing-segmentation/
│── classified/
│── dataset/
│── enhanced/
│── ground_truth/
│── output/
│── segmented/
│── main.ipynb
│── image_quality_metrics.xlsx
│── requirements.txt
└── README.md
```

---

## Results

- Enhanced low-light CCTV images with improved brightness and contrast.
- Successfully segmented regions of interest using Otsu's Thresholding.
- Extracted Histogram and GLCM features for classification.
- Random Forest classifier effectively classified person and non-person objects.

---

## Future Improvements

- Real-time CCTV video enhancement
- YOLOv8-based object detection
- Deep learning-based image enhancement

---

## Author

**Paruvatha Priya B**
