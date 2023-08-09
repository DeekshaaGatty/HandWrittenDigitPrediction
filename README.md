
# Handwritten Digit Classification using Random Forest

This repository contains a Python-based analysis of handwritten digit recognition using a Random Forest Classifier. The objective of this project is to build and evaluate a machine learning model that can classify images of handwritten digits (0 to 9) accurately.

## Dataset

The analysis utilizes the "Digits" dataset from scikit-learn (sklearn). The dataset consists of a collection of 8x8 images, each representing a handwritten digit, along with corresponding labels.

- Total Number of Images: 1797
- Image Dimensions: 8x8 pixels
- Number of Classes: 10 (digits from 0 to 9)

## Analysis Steps

1. **Data Loading and Description**: The dataset is loaded and its properties, such as the number of samples, features, and label distribution, are described.

2. **Data Visualization**: A subset of images from the dataset is visualized to provide a glimpse of the handwritten digits.

3. **Data Preprocessing**: The images are flattened and pixel values are scaled to [0, 1] range for preprocessing.

4. **Train-Test Split**: The dataset is split into training and testing sets to train and evaluate the model.

5. **Modeling**: A Random Forest Classifier is employed to learn patterns in the training data.

6. **Prediction**: The trained model is used to predict the labels of the test data.

7. **Model Evaluation**: The model's performance is assessed using a confusion matrix and a classification report, which includes precision, recall, F1-score, and support metrics for each class.

## Getting Started

To run the analysis on your local machine:

1. Clone this repository: `git clone https://github.com/DeekshaaGatty/HandWrittenDigitPrediction.git`
2. Navigate to the project directory: `cd handwritten-digit-classification`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the analysis: Open and execute the Jupyter notebook `Handwritten_Digit_Classification.ipynb`.

Feel free to modify and experiment with the code to deepen your understanding of the classification process and explore different techniques.

## Results

The analysis demonstrates the effectiveness of the Random Forest Classifier in accurately classifying handwritten digits. The confusion matrix and classification report provide insights into the model's performance on the test data.
