# Thesis Code Repository

Welcome to the GitHub repository for my thesis project, which focuses on improving the accuracy and robustness of semantic segmentation and environment recognition in indoor environments. This repository contains the code and associated files for the project.

## Table of Contents
- [Introduction](#introduction)
- [Code Overview](#code-overview)
- [Dependencies and Usage](#dependencies-and-usage)
- [Future Work](#future-work)
- [References](#references)

## Introduction

The field of robotics and XR (Extended Reality) devices is experiencing rapid growth, and the accurate understanding and interaction with the environment are crucial for their success. This project leverages RGB-D cameras to scan spaces, detect objects, and improve semantic segmentation and environment recognition. Here's a breakdown of what this code does:

### Semantic Segmentation

The code uses a deep learning model to perform semantic segmentation, which involves classifying each pixel in an image or point in a 3D cloud into specific categories, such as walls, floors, objects, etc. This information provides additional context about the environment, allowing for interactions with objects.

### Environment Recognition

Environment recognition is the process of identifying the type of environment in which a robot or XR device is operating, such as an office, restaurant, library, or home. The code aims to continuously update information about the environment and improve recognition accuracy.

### Key Terminologies

Before diving into the technical details, it's essential to understand some key terminologies used in the code:

- **Deep Learning**: A type of machine learning that utilizes artificial neural networks with multiple layers for tasks like object detection, semantic segmentation, and environment recognition.
- **Semantic Segmentation**: The process of classifying each pixel in an image or point in a 3D cloud into specific categories.
- **Instance Segmentation**: A type of semantic segmentation that not only classifies pixels or points but also distinguishes between individual instances of the same category.

## Code Overview

The code performs the following tasks:

- Loads pre-trained models for semantic segmentation.
- Processes an input image and performs semantic segmentation on it.
- Utilizes a classifier to recognize the environment based on the segmented objects.
- Provides classification metrics and visualizations to assess the recognition performance.

## Dependencies and Usage

To run this code, ensure you have the necessary dependencies installed. The code also uses pre-trained models and dataset files from the [semantic-segmentation-pytorch repository](https://github.com/CSAILVision/semantic-segmentation-pytorch). Be sure to download and set up those files according to the instructions provided in the repository.

## Future Work

The code presents an initial solution for improving semantic segmentation and environment recognition. However, there is still room for improvement and exploration of new techniques. Future work might involve conducting experiments and studies to enhance the overall accuracy and efficiency of the algorithms.

## References

1. [Semantic Segmentation PyTorch Repository](https://github.com/CSAILVision/semantic-segmentation-pytorch): The code in this repository utilizes pre-trained models and dataset files from this source.

Feel free to explore the code and the associated files to gain insights into the project's implementation and results.

For any questions or collaboration opportunities, please feel free to contact me. Thank you for your interest in my thesis project!
