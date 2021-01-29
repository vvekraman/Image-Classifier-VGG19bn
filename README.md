# Image-Classifier-VGG19bn
Creating an Image Classifier using transfer learning as a part of the Deep Learning Course.
A pretained 19 layer VGG model with Batch Normalization is used.
The classifier is modified and the feature layer is kept frozen.

# Dataset
The data set consists of 3726 images divided among 8 classes with slight variations in number. All images are of different resolutions and PIL library is used in resizing them to 3 x 224 x 224 as it is the preferred input dim for the vgg modles. The prediciton set consists of 160 images in total. The train test data split is in random with a ratio of 80:20.

# Performance stats
Using vgg19 with batch normalization resulted in a prediciton score of 92.5%.  
The corresponding model has the below stats,
 * Train Loss: 0.0012  
 * Train Acc: 97.58
 * Validation Loss:  0.006552678989820762  
 * Validation Acc:  88.73994638069705
