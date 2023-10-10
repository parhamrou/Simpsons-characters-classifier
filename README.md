# Simpsons Character Classification using CNN

This project focuses on classifying Simpsons characters using a Convolutional Neural Network (CNN). The objective is to accurately identify and categorize characters from the popular TV show, The Simpsons.

## Dataset

We utilized a publicly available dataset of Simpson character images obtained from Kaggle. The dataset comprises a total of 41,866 images. To streamline the classification task, we initially focused on the ten characters with the highest number of pictures within the dataset. These ten characters were selected as the target classes for classification.

## Methodology

To achieve optimal classification accuracy, we conducted experiments with various hyperparameters. These included the learning rate, optimizer, and number of epochs. By systematically adjusting these parameters, we aimed to identify the ideal combination that maximized the accuracy of the model. In our experiments, we employed the Adam optimizer with a learning rate of 0.001 and trained the model for 100 epochs. Additionally, we implemented early stopping to prevent overfitting and enhance generalization.

## Libraries Used

The following libraries were utilized in this project:

- Keras
- Sklearn
- OpenCV
- Caer

These libraries provided essential functionalities for building and training the CNN model, as well as performing image processing tasks.

Please refer to the documentation and installation guides for each library to ensure proper setup and usage.

Feel free to explore the code and adapt it to your specific requirements.
