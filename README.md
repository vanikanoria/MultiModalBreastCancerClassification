# Multimodal Breast Cancer Detection

This repository contains the code and resources for the study on **Multimodal Breast Cancer Detection**, which integrates mammogram imaging data and textual clinical data to improve diagnostic accuracy. The work explores the potential of multimodal deep learning frameworks for advancing medical diagnostics.

## Abstract

This study presents a multimodal deep learning framework for breast cancer diagnosis, combining imaging features from mammograms with clinical data. Using the CBIS-DDSM dataset, we preprocess and integrate these data types for unified analysis. Several architectures were evaluated, including:

- **Image-only baseline**: ResNet
- **Multimodal combinations**: CLIP, BERT, ResNet, and Vision Transformers (ViT)

The **BERT-ViT** configuration demonstrated the highest accuracy, with significant improvements over the ResNet baseline. The findings underscore the potential of multimodal learning for enhanced breast cancer detection and clinical decision support.

## Features

- **Data Preprocessing**: Steps to preprocess imaging and clinical features from the CBIS-DDSM dataset.
- **Model Architectures**: Implementation of baseline (ResNet) and multimodal models (BERT, ViT, CLIP).
- **Evaluation**: Comprehensive performance comparison of different model architectures.

## Authors

- Adwait Agashe  
- Renu Jadhav  
- Uday Malhotra  
- Vani Kanoria  

## Results
The BERT-ViT model achieved a test accuracy of 86.36%, representing a 25% improvement over the ResNet baseline.
