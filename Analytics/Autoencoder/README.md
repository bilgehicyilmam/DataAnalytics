# Autoencoder

Autoencoder is an unsupervised artificial neural network that compresses the input into a lower-dimensional space and then reconstructs the output from this representation. 

Autoencoders consists of 4 main parts:

1- Encoder: In which the model learns how to reduce the input dimensions and compress the input data into an encoded representation.

2- Bottleneck: which is the layer that contains the compressed representation of the input data. This is the lowest possible dimension of the input data.

3- Decoder: In which the model learns how to reconstruct the data from the encoded representation to be as close to the original input as possible.

4- Reconstruction Loss: This is the method that measures how well the decoder is performing and how close the output is to the original input.

![image](https://user-images.githubusercontent.com/61224886/93333921-bb216980-f82c-11ea-9fcd-fb626b64dd6a.png)

# Output 

![image](https://user-images.githubusercontent.com/61224886/93335740-911d7680-f82f-11ea-8af7-a034cd64f125.png)

The model is trained with nonfraudulent transactions, and learned how to separate different examples (fraudulent cases). 
Reconstruction error is quite high for the fraudulent cases since the model see these data points for the first time. Since we trained the model with just nonfraudulent cases,
reconstruction error is quite low for nonfraudulent cases.



