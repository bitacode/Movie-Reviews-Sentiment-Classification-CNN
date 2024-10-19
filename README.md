# Sentiment Classification with CNN

## Introduction

A Convolutional Neural Network (CNN) is a class of deep neural networks that is widely used for analyzing visual data. They are particularly effective for tasks involving image classification, object detection, facial recognition, and more. CNNs are inspired by the organization of the visual cortex, the part of the brain responsible for processing visual information.

In NLP, text data can be represented as a sequence of words or characters, which can be thought of as a one-dimensional grid. CNNs are effective in NLP because words in a sentence or phrases have contextual relationships, just like in images, where pixels close to each other have a relationship.

## Dataset

This experiment employs a dataset that comprises movie reviews. The dataset used for model training is publicly available on Kaggle and accessible for free on the internet. The link to this data is [Kaggle Rotten Tomatoes EDA](https://www.kaggle.com/code/stefanoleone992/rotten-tomatoes-eda). The movie reviews were annotated using [RoBERTa](https://github.com/bitacode/Labeling-Dataset-For-Sentiment-Analysis.git).

## Results

The CNN model achieved a training loss of 0.3791 with an accuracy of 88.4%. On the validation set, the model obtained a loss of 0.6511 and an accuracy of 78.59%. These results indicate that the model performs well on the training data, with some overfitting observed on the validation set, as reflected in the higher validation loss and lower accuracy.

For the positive class, the model obtained a precision of 0.85, a recall of 0.83, and an F1-score of 0.84. The negative class resulted in a precision of 0.82, recall of 0.81, and an F1-score of 0.81. The neutral class had a lower performance, with a precision of 0.69, recall of 0.71, and an F1-score of 0.70. The macro and weighted averages for precision, recall, and F1-score were all consistent at 0.78, indicating balanced performance across all classes.

## Prospects
The CNN model layers can be further customized to increase complexity, allowing it to capture more intricate patterns in the data. Additionally, techniques such as regularization, learning rate scheduler, and early stopping parameters can be adjusted to help overcome the overfitting observed in the validation results. These improvements could potentially enhance the model's generalization performance and increase its overall accuracy.


