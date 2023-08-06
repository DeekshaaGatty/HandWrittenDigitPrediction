# HandWrittenDigitPrediction
Training a Random Forest Classifier to classify images of handwritten digits from 0 to 9 using the "Digits" dataset 

The steps followed in the process are as follows:

1)Data Exploration: The dataset contains a total of 1,797 images of handwritten digits. Each image is an 8x8 pixel grayscale image. There are 10 classes representing digits from 0 to 9, and the class distribution is approximately balanced.

2)Data Visualization: A subset of the images is visualized using matplotlib to get an idea of the digit samples present in the dataset.

3)Data Preprocessing: The images are flattened to create feature vectors. The pixel values of the images are scaled to the range [0, 1] by dividing them by 16.

4)Data Splitting: The dataset is split into training and testing sets using a 70-30 ratio.

5)Modeling: A Random Forest Classifier is used to train the model on the training data.

6)Prediction: The model makes predictions on the test data.

7)Model Evaluation: The performance of the model is evaluated using the confusion matrix and a classification report. The classification report provides metrics such as precision, recall, F1-score, and support for each class, giving a comprehensive overview of the model's performance.
