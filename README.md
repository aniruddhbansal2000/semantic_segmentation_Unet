# Semantic Segmentation using U-Net on Cityscape Dataset

- Image Segmentation is widely studied problem in field of Computer vision and image processing. Using Deep Learning based methods have allowed significant improvements in the field.

- Semantic Segmentation is an activity in pixel level classification of image is performed i.e. each pixel of image is assigned into different classes. This has wide applications for improving machine vision and allowing for identifying different objects in image.
- We use U-net, an FCN (Fully Convolutional Network) to perform pixel level segmentation. The network is only composed on Convolutional layers and unlike conventional ConvNet it performs Upsampling (increasing object dimensions) using transpose convolution layers.

Dataset
- The dataset used is the CityScapse Image Dataset
- https://www.kaggle.com/dansbecker/cityscapes-image-pairs
- It contains 2975 train images and 500 validation images
