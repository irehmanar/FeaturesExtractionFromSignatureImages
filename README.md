# Offline Signature Verification

This project implements an offline signature verification system using feature engineering techniques. It extracts various features from signature images for verification purposes, including centroid analysis, black-to-white transitions, and aspect ratios.

## Features

- **Signature Bounding Box Detection**: Detects the bounding box around the signature in the image.
- **Centroid Calculation**: Computes the centroid of the signature for analysis.
- **Hierarchical Image Segmentation**: Divides the image into 64 cells for detailed analysis.

### Feature Extraction Techniques

- **Black to White Transitions**: Analyzes transitions from black to white pixels in the signature.
- **Cell-wise Centroid Coordinates**: Extracts centroid coordinates for each segmented cell.
- **Aspect Ratio Analysis**: Evaluates the aspect ratios of the signature.
- **Skew and Slant Angle Computation**: Calculates the skew and slant angles of the signature.

### Signature Stability Analysis

- Generates a feature set for reference signatures to evaluate stability and consistency.

## Prerequisites

- Python 3.x
- Required libraries:
  - PIL (Python Imaging Library) or OpenCV
  - NumPy
  - opencv

