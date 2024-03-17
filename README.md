# Gender-Age-Prediction
This project focuses on gender and age detection using the UTK Crop Faces dataset. The goal is to accurately classify the gender and approximate age group of individuals based on facial images.

# Dataset
The UTK Crop Faces dataset is utilized, which provides a collection of cropped facial images with corresponding labels for gender and age. The dataset contains a diverse range of individuals spanning different ages and genders.

# Methodology
The project employs a combination of Convolutional Neural Networks (CNNs) and Support Vector Machines (SVMs) for gender and age detection. The CNN model is responsible for extracting meaningful features from the facial images, while the SVM classifier is employed for the final classification.

# Implementation
### The project consists of the following main steps:

Data Preprocessing: The UTK Crop Faces dataset is prepared by performing necessary preprocessing steps, including resizing, normalization, and data augmentation techniques.

CNN Feature Extraction: A CNN model is trained on the preprocessed facial images to extract discriminative features that capture the gender and age-related characteristics.

SVM Classification: The extracted features from the CNN are fed into an SVM classifier, which is trained to classify the gender and approximate age group of individuals.

Evaluation: The trained model is evaluated on a separate test set to measure its performance in terms of gender and age detection accuracy.

### Results
The project provides insights into the effectiveness of using CNNs and SVMs for gender and age detection. The evaluation results demonstrate the accuracy achieved by the model on the UTK Crop Faces dataset.

# Usage
To use the project, follow these steps:
Download the UTK Crop Faces dataset and ensure it is properly organized.
Run the data preprocessing script to preprocess the images.
Train the CNN model to extract facial features.
Train the SVM classifier using the extracted features.
Evaluate the trained model on the test set to measure performance.
Dependencies

### The project requires the following Dependencies:
  - Python
  - TensorFlow 
  - scikit-learn 
  - OpenCV 
  - NumPy
    
Ensure that these dependencies are installed and configured correctly before running the project.

# Credits
The UTK Crop Faces dataset used in this project is provided by [Kaggle] and should be appropriately credited.
