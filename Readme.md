# Multi-Category-Semantic-Segmentation-on-CT-scans-Using-Deep-Neural-Networks

**Author:** BAIM Mohamed Jalal  
**Student ID:** 313551810  
**Date:** November 20, 2024

---

## Overview

This repository contains implementations of various deep learning models for medical image processing tasks. The models are designed to perform image segmentation on a given dataset. The following notebooks are included:

1. **Deeplabv3Model.ipynb**: Implements the DeepLabv3 architecture for image segmentation.
2. **UnetplusplusModel.ipynb**: Implements the UNet++ architecture for image segmentation.
3. **SelfMadeModel.ipynb**: Introduces a custom architecture proposed by the author, applied to the dataset.

---
## Proposed Model
![ModelSelfMade](https://github.com/user-attachments/assets/2af4212a-8cb9-4d0c-bd86-49f9e64780ed)
---
## Repository Structure

├──codePackage
├── Deeplabv3Model.ipynb
├── UnetplusplusModel.ipynb
├── SelfMadeModel.ipynb
├── README.md

## Update Dataset Paths

In each notebook, locate the Paths section (typically the second cell) and update the paths to point to your local dataset directories.

```python
# Paths
train_img_dir = "/path/to/your/dataset/train_imgs"
train_label_dir = "/path/to/your/dataset/train_lbs"
test_img_dir = "/path/to/your/dataset/test_imgs"
```
