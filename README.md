CNN(Convolutional Neural Network):

Deep learning is an Artificial Intelligence feature that mimics how the human brain works when it processes data to create patterns for decision making.

![image](https://user-images.githubusercontent.com/60400054/175101360-ea0a54ba-fc93-413e-b811-570f9dcf276a.png)

CNN is nothing but a convolutional neural network. A CNN consists of an input layer, an output layer, and some hidden layers. The hidden layer of the CNN has a series of convolution layers that convolve with  multiplication or other inner products. The activation function is usually the RELU layer, followed by additional convolutions such as pool  layers, fully connected layers, and normalized layers. These inputs and outputs are called hidden layers because they are masked by the activation function and the final convolution. This is basically a moving dot product or cross-correlation. These CNN layers convolve the input and pass the result to the next layer.

Basic Architecure of CNN:

The basic architecture of the CNN model is

1)	Input Layer

2)	Convolution Layer 

3)	Pooling Layer 

4)	Fully Connected Layer

5)	Output Layer

![image](https://user-images.githubusercontent.com/60400054/175101783-e994ebd9-77a0-4996-9efb-3723c54d8c88.png)

 
               Fig: Basic Architecure of CNN model

1) Input Layer : The input image is the image given to the model to perform various functions and inspect the output. It is given to a block called a convolutional layer.

2) Convolution Layer : Convolution is the first layer to extract features from a given input image. Convolution restores the relationships between pixels by learning the features of the image  using small squares of the input data. This is a math operation that takes two inputs, like an image matrix and a filter.

3) Pooling Layer : In the Pool Layer section, reduce the number of parameters if the image is too large. Spatial pooling, also known as subsampling or downsampling, reduces the dimensions of each map without changing  important information. 
There are three types of spatial pooling : 

•	Max Pooling : Maximum pooling gets the largest element from the modified feature map. Calls the sum of all the elements in the feature map  as a sum total.

•	Average Pooling : If you want to take the biggest factor, you can also take the average pooling.

•	 Sum Pooling: Calls the sum of all the elements in the feature map  as a sum pooling.

![image](https://user-images.githubusercontent.com/60400054/175101941-d8e3c6cb-9735-4b6a-96b5-3cbc191cbe5a.png)

     
                            Fig: Pooling
4)  Fully Connected Layer : 

A layer called the FC layer flattens the matrix into vectors and feeds them into a fully connected layer like a neural network. 
Fully connected layers combine all the features  to create a model. Finally, use activation functions such as Softmax and Sigmoid to classify exits into cats, dogs, apple, bus and so on.

![image](https://user-images.githubusercontent.com/60400054/175102087-7978c250-61ad-44a5-bf07-0ed59a73c52c.png)

 
                          Fig: FC Layer

5)	Output Layer : 

The output image provides the result of the model. The output is based on a fully connected layer.
