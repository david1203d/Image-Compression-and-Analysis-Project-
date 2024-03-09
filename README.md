# Pixel Perfect: Advanced Image Processing Techniques

## Overview
This project encompasses a suite of MATLAB functions designed for the compression and analysis of images through Singular Value Decomposition (SVD) and Principal Component Analysis (PCA). It aims to explore the application of these mathematical techniques for reducing image storage space while minimally impacting image quality and for performing dimensionality reduction on image data for analysis.

## Files and Their Functions

### `prepare_data.m`
- **Purpose**: Loads and prepares the MNIST dataset for training purposes.
- **Functionality**: This script extracts a specified number of images and their corresponding labels from a given file, setting the stage for model training.

### `prepare_photo.m`
- **Purpose**: Prepares an image for analysis and processing.
- **Functionality**: It converts the image into a format suitable for further processing, applying necessary preprocessing steps to standardize input data.

### `task1.m`
- **Purpose**: Implements image compression using SVD by retaining a specified number of singular values.
- **Functionality**: This function compresses an image by reducing the number of singular values used in its representation, effectively decreasing the image size.

### `task2.m`
- **Purpose**: Applies Principal Component Analysis (PCA) to approximate an image.
- **Functionality**: It reduces the dimensionality of the image data by utilizing a specified number of principal components, aiding in data simplification and storage efficiency.

### `task3.m`
- **Purpose**: Enhances the application of PCA on image data for improved approximation.
- **Functionality**: Utilizes PCA to achieve a more compact representation of an image based on a predetermined number of principal components, optimizing for both compression and quality.

### `visualise_image.m`
- **Purpose**: Visualizes specific images from the dataset.
- **Functionality**: This script extracts and displays a particular image from the training matrix, facilitating visual inspection and verification of data processing.

### `classifyImage.m`
- **Purpose**: Classifies an image using PCA and k-nearest neighbors.
- **Functionality**: Processes an image for classification based on features extracted through PCA and categorizes it using the k-NN algorithm, blending dimensionality reduction with machine learning for accurate results.

### `KNN.m`
- **Purpose**: Implements the k-nearest neighbors algorithm for classification.
- **Functionality**: Employs distances between data points to classify images into predefined categories, showcasing a fundamental approach to pattern recognition.

### `magic_with_pca.m`
- **Purpose**: Applies PCA "magic" on the training dataset.
- **Functionality**: Processes the dataset with PCA to enhance data features before classification, demonstrating how PCA can be used to improve machine learning model performance.

## Usage Instructions
To utilize the functionalities provided in this project, ensure access to the MNIST dataset and suitable images for processing. Each script should be executed within the MATLAB environment, following the specific instructions provided within each file's comments. Ensure all dependencies are met and that the path to your dataset is correctly configured within the scripts.
