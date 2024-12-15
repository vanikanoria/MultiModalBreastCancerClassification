# Multimodal Breast Cancer Detection

This repository contains the code and resources for the study on **Multimodal Breast Cancer Detection**, which integrates mammogram imaging data and textual clinical data to improve diagnostic accuracy. The work explores the potential of multimodal deep learning frameworks for advancing medical diagnostics.

## Abstract

This study presents a multimodal deep learning framework for breast cancer diagnosis, combining imaging features from mammograms with clinical data. Using the CBIS-DDSM dataset, we preprocess and integrate these data types for unified analysis. Several architectures were evaluated, including:

- **Image-only baseline**: ResNet
- **Multimodal combinations**: CLIP, BERT, ResNet, and Vision Transformers (ViT)

The **BERT-ViT** configuration demonstrated the highest accuracy, with significant improvements over the ResNet baseline. The findings underscore the potential of multimodal learning for enhanced breast cancer detection and clinical decision support.

## Features

### Data Preprocessing
- Preprocessing steps for both mammogram images and clinical metadata to ensure compatibility for model training.
- Handling of missing or inconsistent data, normalization of clinical features, and resizing of images for uniform input.

### Model Architectures
- **ResNet**: A convolutional neural network (CNN) used as a baseline for image-based classification.
- **CLIP**: Combines image and text features, providing a mechanism for joint representation learning.
- **BERT**: Used for encoding clinical textual data, allowing the model to integrate rich, unstructured clinical notes.
- **Vision Transformers (ViT)**: An alternative architecture for image classification, based on transformer models.

<img width="1073" alt="Architecture" src="https://github.com/user-attachments/assets/cc6be5c0-4958-481d-8724-8f4b7af879e1" />

### Evaluation
- Performance evaluation of the models using standard metrics such as accuracy, precision, recall, and F1 score.
- Comparative analysis of image-only versus multimodal models to demonstrate the added value of clinical data in improving diagnostic performance.

## Authors

- Adwait Agashe  
- Renu Jadhav  
- Uday Malhotra  
- Vani Kanoria

## Results

	•	The BERT-ViT multimodal model achieved the highest test accuracy of 86.36%, showing a 25% improvement over the ResNet baseline model (68.5% accuracy).
	•	The multimodal models consistently outperformed the image-only models across all evaluation metrics, demonstrating the added value of integrating clinical textual data alongside mammogram images.
