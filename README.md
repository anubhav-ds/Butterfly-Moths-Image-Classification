# Butterfly-Moths-Image-Classification
Butterfly &amp; Moths Image Classification for 100 Species

This project aims to produce a CNN model with which we can classify the different species of Butterflies and Moths. Generally for most of us there is almost no difference between Butterflies and Moths, due to this general bayes error is quite and only for experts it will be quite low.

Our goal here is to train a model which is high in accuracy and also efficient to some degree, for this we will use two different CNN Architectures, MobileNet V2 and Inception-Resnet. MobileNet V2 and generally all MobileNet are more efficient because of using depth wise convolution. And Inception with Skip connections or Inception-Resnet will be more deeper and more complex model. We will compare accuracy and efficiency of both models and give appropriate conclusion.

The dataset has been sourced from this link:https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species?select=butterflies+and+moths.csv

We have been provided with 3 Data Sets:

Train set consists of 12594 images partitioned into 100 sub directories one for each species.
Test set consists of 500 images partitioned into 100 sub directories with 5 test images per species.
Valid set consists of 500 images partitioned into 100 sub directories with 5 validation images per species.
Size of the images is 224,224,3 for height= width = 224 and RGB channels. This project was done on Kaggle free environment with GPU P100. Training time may vary in different environments.
