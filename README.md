# Alzheimer-Classification
This repository contains the code and framework for multiple neural network models designed to classify Alzheimer's disease using multimodal data, including MRI images. I made this to experiment with and learn about pretrianed models, Neural Network frameworks, and computer vision. The model was fine-tuned on pre-trained computer vision architectures such as ResNet50, CLIP, and DenseNet121.

## Overview
This project aims to provide an efficient and accurate deep learning solution for the classification of Alzheimer's disease. The framework leverages state-of-the-art convolutional neural networks (CNNs) and multimodal data inputs to detect Alzheimer's across different stages. The neural network was fine-tuned using MRI image datasets.

### Features
- **Multimodal Data**: Trains on MRI images and other relevant modalities to improve classification accuracy.
- **Pre-trained Models**: Utilizes the power of pre-trained models such as:
  - **ResNet50** for robust feature extraction.
  - **CLIP** for image-text embeddings.
  - **DenseNet121** for efficient feature propagation and deep representation learning.
- **Fine-tuning**: The models are fine-tuned on Alzheimer's data to optimize for disease classification tasks.
- **Lightweight Framework**: Designed to be modular and lightweight, enabling easy experimentation with different neural architectures and datasets.

## Data
I have used the following datasets:
- [MRI and Alzheimer's Dataset on Kaggle](https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers/code)
- [Alzheimer's Dataset and Discussion on Kaggle](https://www.kaggle.com/datasets/yasserhessein/dataset-alzheimer/discussion?sort=hotness)
