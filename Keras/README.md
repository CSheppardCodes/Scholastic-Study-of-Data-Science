# TensorFlowMonkeyClassification README

## Overview

This project focuses on the classification of different monkey species using convolutional neural networks (CNNs). The dataset consists of images of various monkey species, and the goal is to build a model capable of accurately classifying these species based on their images.

## Dataset

The dataset used in this project is sourced from the [TFMonkeyClassification](https://github.com/CSheppardCodes/TFMonkeyClassification) repository. It contains images of ten different monkey species, with corresponding training and validation sets.

### Labels
- **n0:** mantled_howler
- **n1:** patas_monkey
- **n2:** bald_uakari
- **n3:** japanese_macaque
- **n4:** pygmy_marmoset
- **n5:** white_headed_capuchin
- **n6:** silvery_marmoset
- **n7:** common_squirrel_monkey
- **n8:** black_headed_night_monkey
- **n9:** nilgiri_langur

## File Structure

- **/content/TFMonkeyClassification/:** The main project directory containing training and validation data.
- **/content/TFMonkeyClassification/training/:** Training images organized by species.
- **/content/TFMonkeyClassification/validation/:** Validation images organized by species.
- **/content/drive/:** Google Drive mount point for storage and file access.

## Code Overview

The project involves the following major steps:

1. **Data Preprocessing:**
   - Loading and organizing the dataset.
   - Preprocessing images for model input.

2. **Model Building:**
   - Implementing a Convolutional Neural Network (CNN) for image classification.
   - Used **mobilenet_v3_large_100_224** from TensorFlow Hub for feature extraction.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/599ce41c-f971-4157-81e1-107876e5f0a4)

3. **Training:**
   - Splitting the data into training and testing sets.
   - Training the model on the training set.
   - Evaluating the model on the testing set.
     
   Epoch 5/5:
   - **Training Loss:** 0.0149
   - **Training Categorical Accuracy:** 1.0000
   
   - **Validation Loss:** 0.1223
   - **Validation Categorical Accuracy:** 0.9706


4. **Results Visualization:**
   - Displaying sample images and their corresponding predictions.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/26cf6568-5ae7-44b2-81c0-2a436d8088a0)

## Environment Setup

To run the code, ensure you have the required libraries and dependencies installed. The project utilizes popular libraries such as TensorFlow, Keras, OpenCV, and others. You can install them using:

```bash
pip install tensorflow opencv-python pandas numpy scikit-learn imbalanced-learn tqdm
