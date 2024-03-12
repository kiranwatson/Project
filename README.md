# Glaucoma Detection Using InceptionV3 Model 
### Introduction 
Glaucoma is a leading cause of irreversible blindness worldwide. Early detection and treatment are crucial to prevent vision loss. This repository contains code for Glaucoma detection using a convolutional neural network (CNN) architecture based on the InceptionV3 model. The process involves collecting, organizing, and preprocessing Glaucoma image datasets from multiple sources, followed by training the InceptionV3 model for Glaucoma detection .
### Data Preprocessing
1. Dataset Collection:   Glaucoma datasets are collected from various sources, including Dristhi, Rim One, and ACRIMA datasets.
2. Combining Datasets:   Images from different datasets are combined into a single directory structure.
3. Invalid Image Handling: Invalid images are identified and skipped during preprocessing.
4. Image Resizing: Images are resized to a standard size (299x299 pixels) for model input.
5. Data Augmentation: Data augmentation techniques such as rotation, shifting, shearing, zooming, and flipping are applied to increase the dataset's diversity.
### Model Training
1. Model Compilation: The InceptionV3-based model is compiled with binary cross-entropy loss and RMSprop optimizer.
2. Callbacks: Reduce learning rate and early stopping callbacks are employed to prevent overfitting.
3. Training: The model is trained on the preprocessed datasets with the specified parameters (epochs, batch size, etc.).
### Results
After training the model, the validation accuracy is evaluated to assess its performance in Glaucoma detection.
### Dependencies
Ensure you have the following dependencies installed:

Python (>=3.6)
TensorFlow
Keras
NumPy
Matplotlib
Seaborn
PIL (Python Imaging Library)
### Execution Format:
1. Data_Preporation.ipnpy file
2. Final_model.ipnby file 
