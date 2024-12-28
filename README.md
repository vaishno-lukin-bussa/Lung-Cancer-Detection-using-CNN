# Lung Cancer Image Classification
Here is a basic example of the deep learning-based solution for lung cancer image classification involving convolutional neural networks (CNN): This particula falls under three main classes.
- lung_n: Normal lung tissue.
- lung_aca: Adenocarcinoma.
- lung_scc: Squamous cell carcinoma.

## Project Overview
The major aim of this project is to train a Convolutional Neural Network (CNN) to classify these images into the abovementioned three categories. Data has been pre-processed, segmented into training and validation sets, and used as input for a CNN model having multiple convolutional layers, pooling layers, and dense layers.

## Features
## Image Preprocessing:
- resizing images to be of the standard size 256x256.
## CNN Architecture:
  - 3 conv layers + ReLU activation.
  - Max pooling to reduce dimensions.
  - Fully connected with dropout and batch normalization.
## Callbacks:
  - Early stopping to avoid overfitting.
  - Learning rate reduction on plateau for adaptive optimization.
## Performance Metrics:
  - Confusion matrix and classification report.
## Dataset
- The dataset is contained in a ZIP file located at: `/content/drive/MyDrive/lung_cancer_dataset/lung_cancer.zip`.
- Extracted images fall into subcategories of:
  - `lung_n` (Normal)
  - `lung_aca` (Adenocarcinoma)
  - `lung_scc` (Squamous Cell Carcinoma)
## Future Improvements
- Must Train the model for more epochs with larger datasets for a good accuracy.
- We can train the model with transfer learning using pretrained models like VGG16 or ResNet.
- We can deploy the model as a web app for real-time classification.
