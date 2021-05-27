# Semantic Segmentation using U-Net on Cityscape Dataset

Image Captioning is a widely studied research problem with a wide variety of applications. We propose to make the traditional image captioning baseline achieve a higher accuracy by a multimodal semantic space loss. Concretely, we map the visual feature space to the same feature space as the word embedding and formulate a similarity objective while jointly optimizing the binary cross entropy. This ensures a tight coupling between the two semantic spaces; namely word embedding and image features.


- Image Segmentation is widely studied problem in field of Computer vision and image processing. Using Deep Learning based methods have allowed significant improvements in the field.

- Semantic Segmentation is an activity in pixel level classification of image is performed i.e. each pixel of image is assigned into different classes. This has wide applications for improving machine vision and allowing for identifying different objects in image.
- We use U-net, an FCN (Fully Convolutional Network) to perform pixel level segmentation. The network is only composed on Convolutional layers and unlike conventional ConvNet it performs Upsampling (increasing object dimensions) using transpose convolution layers.

Dataset
- The dataset used is the CityScapse Image Dataset
- https://www.kaggle.com/dansbecker/cityscapes-image-pairs
- It contains 2975 train images and 500 validation images
