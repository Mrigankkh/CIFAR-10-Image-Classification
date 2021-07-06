# CIFAR-10-Image-Classification

In this project, I have classified images from the CIFAR-10 dataset  using CNN and ResNet model.. The dataset consists of airplanes, dogs, cats, and other objects.I have  trained my model on Google Colab using thousands of images in the training set and attained an accuracy of 90.31% against the test set.

# Contents
1. Python Libraries
2. Understanding the dataset
3. Key- points
4. Model Architecture 
5. Training the model
6. Prediction

#  Python Libraries
Open CV

Numpy

Torch

Torchvision

Matplotlib

# Understanding the Dataset
The german CIFAR-10 dataset was used. The original batch data is a(10000 x 3072) dimensional tensor expressed in numpy array, where the number of columns, (10000), indicates the number of sample data. As stated in the CIFAR-10/CIFAR-100 dataset, the row vector, (3072) represents an color image of 32x32 pixels.

# Key-points
Images were normalised and appropriate transforms were apploed for data augmentation which helped increase the accuracy of the model.

# Model Architecture
A modified version of the ResNet-50 model was used.




# Training the model
I trained this model in an online cloud instance on Google Colab over 25 epochs. 

Train accuracy: 93.41%

# Prediction

The model achieved 90.31% accuracy.

!(https://github.com/Mrigankkh/CIFAR-10-Image-Classification/blob/main/result/cifaracc.png)


!(https://github.com/Mrigankkh/CIFAR-10-Image-Classification/blob/main/result/cifarval.png)



