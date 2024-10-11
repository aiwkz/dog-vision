# 🐶 Dog Breed Classification

This repository contains the code for an end-to-end multi-class image classification model to classify dog breeds using deep learning and transfer learning.

## Project Overview
The objective of this project is to classify the breed of a dog given its image. The project uses TensorFlow and TensorFlow Hub to implement transfer learning for building a highly accurate image classifier.

## Data
- The dataset is from the [Kaggle Dog Breed Identification Competition](https://www.kaggle.com/c/dog-breed-identification).
- The dataset contains over 10,000 labeled images of 120 different dog breeds for training and 10,000+ unlabeled images for testing.
- Due to the large size of the data, it is not included in this repository. You can download it from the link above.

## Key Steps
1. **Data Preparation**: Load and preprocess the images.
2. **Modeling**: Use pre-trained models from TensorFlow Hub for transfer learning.
3. **Evaluation**: Evaluate the model on validation data and submit predictions.

## Requirements
- TensorFlow 2.x
- TensorFlow Hub
- NumPy
- Matplotlib

## Results
The model produces a submission file containing prediction probabilities for each test image's breed.

## Usage
1. Clone the repository.
2. Download the dataset from Kaggle and place it in the appropriate directory.
3. Run the Jupyter notebook or Google Colab notebook to train the model and generate predictions.

## Acknowledgments
- Kaggle for providing the dataset and competition framework.
- TensorFlow for making high-performance machine learning tools accessible.

