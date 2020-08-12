# Convolutional Neural Networks

CNN has popularly applied to image classification problems. It is also effectively applied to recommender systems, natural language processing, and more. CNN's biggest benefit is that it identifies the relevant features automatically without any human intervention. 

On the other hand, CNN is computationally efficient. It uses convolution and pooling operations and performs parameter sharing. The required pre-processing phase is much lower as compared to other classification algorithms.

In Convolutional Neural Network, the filter scans the input image and multiplies the kernel with the corresponding receptive field in the input image and adds it all up to get a new pixel in the output activation map.

## Architecture

CNN architectures: Convolutional Layer, Pooling Layer, and Fully-Connected Layer.  

 
![image](https://user-images.githubusercontent.com/61224886/90001949-b4865c00-dc9a-11ea-85a4-c5f948130687.png)


There is an input image, and a series of convolution + pooling operations followed by several fully connected layers.


## Image Classification with CNN (Sign Language)

This study is the analysis of image classification with CNN on the sign language dataset. This dataset contains 2062 (64x64) input images to classify the the numbers [0,1,2,3,4,5,6,7,8,9] in sign language. 

![image](https://user-images.githubusercontent.com/61224886/89738104-b542a680-da7e-11ea-89e3-d0b00bdbef5a.png)

