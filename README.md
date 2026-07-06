# CCTV Low-Light Image Enhancement Project

## Overview
This project performs:
1. Low-light CCTV image enhancement
2. ROI segmentation
3. Feature extraction
4. Object classification (person/non-person example)

## Dataset
- Source: ExDark or your own CCTV images
- Number of images: N
- Image types: Color images converted to grayscale for processing
- Sample images: [Insert screenshots]

## Methodology
1. **Image Enhancement:** Noise reduction, CLAHE, unsharp mask, wavelet multiresolution
2. **Segmentation:** Otsu’s thresholding for ROI extraction
3. **Feature Extraction:** Histogram + GLCM features
4. **Classification:** Random Forest classifier

## Evaluation
- Image quality metrics: PSNR, SSIM
- Classification metrics: Accuracy, Precision, Recall, F1-score

## Results
- Enhanced images are brighter and sharper
- Segmentation accurately isolates objects
- Classification achieves [insert accuracy] on test set
