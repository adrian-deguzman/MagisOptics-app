# Diabetic Retinopathy Classification & Prediction System

This project develops a machine learning-based system for classifying Diabetic Retinopathy (DR) stages using deep learning models. The system is integrated with a Django web application that allows users to upload retinal images and receive real-time predictions. The models used include Decision Tree, ResNet-18, and U-Net CNN, which are trained on the Diabetic Retinopathy dataset.

## Project Overview

Diabetic Retinopathy (DR) is a leading cause of preventable blindness. Early detection and treatment can significantly reduce the risk of vision loss. This project aims to create a basic DR classification system that can assist healthcare providers in diagnosing DR from retinal images.

- **Decision Tree**: A classical model used for its simplicity and good results on smaller datasets.
- **ResNet-18**: A deep convolutional neural network for image classification.
- **U-Net**: A deep learning model specialized in image segmentation, useful for detecting small retinal features.

## Key Features

- **Real-time Prediction**: Upload retinal images to the web application and get predictions on the severity of DR.
- **Model Integration**: The Django app uses three different models to provide classification results.
- **Evaluation**: The models are evaluated with accuracy, precision, recall, and F1-score metrics.
