# Plant Disease Classification with FastAI

## Overview

This Python script focuses on training a convolutional neural network (CNN) using the FastAI library for plant disease classification. The steps include checking GPU information, installing required libraries, loading and preparing the dataset, creating a CNN learner, fine-tuning the model, evaluating results, and saving the trained model.

## How to Use

1. Run the provided commands to check GPU information and install necessary libraries.

2. Mount Google Drive to access the dataset.

3. Copy the dataset zip file from Google Drive and extract it.

4. Run the script to prepare the dataset using FastAI's DataBlock.

## Model Training

- **Creating Learner:** The script creates a convolutional neural network (CNN) learner using the ResNet34 architecture.

- **Model Summary:** The summary of the model architecture is printed.

## Model Fine-tuning

- **Learning Rate Finder:** The script uses FastAI's learning rate finder to determine an optimal learning rate.

- **Fine-tuning the Model:** The model is fine-tuned using the suggested learning rate.

## Model Evaluation

- **Results Display:** The script displays results such as training and validation loss, error rate, and accuracy.

- **Confusion Matrix:** FastAI's interpretation tools are used to generate and plot the confusion matrix.

## Model Saving

- **Exporting Model:** The trained model is exported and saved as "plant_disease_model.pkl".

## Dataset Information

### Description

The PlantVillage dataset consists of healthy and unhealthy leaf images divided into 38 categories by species and disease.

### Data Source

You can download the dataset: https://www.kaggle.com/datasets/emmarex/plantdisease. Different versions of the dataset are present in the raw directory. Use images in the color folder.

## Author

- **Author:** Ilaha Musayeva
- **Date:** 10/28/2023

