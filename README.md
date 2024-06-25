# Semi-supervised Clustering in Image Analysis

## Introduction

In this study, I performed semi-supervised clustering on MNIST dataset. Semi-supervised learning in general is very useful when there is small amount of labeled data and large amount of unlabeled data. There are several powerful methods in this field.

## Data

MNIST dataset contains images of handwritten digits and images are 28x28 pixels which makes 784 when we have the images as vector. In this study, I am making using of only 10% of labeled data out of 60000 data. 

## Method

I have used Unsupervised Clustering using Gaussian Mixture, Supervised using Convolution Neural Network then applied Kmeans clustering to the features extracted by the CNN model and Semi-supervised clustering using LabelSpreading to better understand how well the semi-supervised clustering can work.

While semi-supervised clustering improves performance, there is still room for enhancement, particularly in reducing overlap and increasing cluster purity. !

Accuracy score is calculated for the unlabeled data using the true labels and predicted labels. The acuuracy score obtained is 0.9497. This is the overall accuracy of the model, indicating that approximately 94.97% of the prediction made by the model are correct.

The study presented in this document emphasizes the significant advantages of semi-supervised clustering techniques, highlighting their ability to effectively utilize both labeled and unlabeled data to enhance clustering performance. By leveraging a small amount of labeled data, semi-supervised clustering methods bridge the gap between supervised and unsupervised learning, resulting in more accurate and reliable clustering outcomes. This is particularly beneficial in scenarios where obtaining labeled data is costly, time-consuming, or impractical.
