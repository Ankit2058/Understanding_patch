

# Optimized Xception Learning Model and XgBoost Classifier for Detection of Multiclass Chest Disease from X-ray Images

Shaheed, Kashif, et al. “Optimized Xception Learning Model and XgBoost Classifier for Detection of Multiclass Chest Disease from X-Ray Images.” Diagnostics, vol. 13, no. 15, Aug. 2023, p. 2583. PubMed Central, https://doi.org/10.3390/diagnostics13152583.

## Introduction
- **Initial Methods**: CT scans and radiographic images were historically used for early diagnosis, aiding in the detection of normal and abnormal lung functions.
- **Conventional CAD Systems**:
  - Used image processing, machine learning (ML), and deep learning (DL).
  - These systems had several drawbacks.

## Disadvantages of CAD Systems
1. Did not provide a generalized solution.
2. Required extensive hyper-parameter tuning.
3. Computational inefficiency with large datasets.
4. High computational complexity of DL models:
   - Required significant memory costs.
   - Challenging to train an efficient model.

## Proposed Solution
- **Inception Model**: 
  - Enhanced to recognize and classify four categories of chest X-ray images.
  - Improved detection capabilities by combining advanced feature extraction with efficient computational processing.

## Problem Statement
- COVID-19 detection relied heavily on chest X-ray scans:
  - Scans were widely available.
  - Detection required the expertise of a skilled radiologist.

## Solution Overview
- **Hybrid Model**:
  - Utilized a pre-trained ResNet combined with a modified Xception module (m-Xception).
  - Extracted high-quality visual features of lung diseases, enhancing the accuracy of classification.

## Data Acquisition
- [Datasets](https://www.kaggle.com/tawsifurrahman/covid19radiography-database)
  - Public datasets provided by Tawsifur-Rehman.
  - Included chest X-ray images categorized into four classes:
    - COVID-19
    - Lung opacity
    - Normal
    - Viral pneumonia


