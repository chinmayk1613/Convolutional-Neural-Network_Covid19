# Convolutional-Neural-Network_Covid19

Convolutional Neural Network is the class of deep learning which is mostly used in computer vision technologies. Unlike the traditional algorithms CNN has two sets of operations called "Convolution" and "Pooling" which results the image into desire features and based on these features understanding and classifying the images. Below are the important layers which is used in CNN.

<code>__1. Convolutional Layer:__</code> In this layer we create a 'kernel' of specific size(5X5 or 7X7) and placed over the image. This operation is actually dot product of original pixel of images within that kernel size and the values defined in the kernel. After the operation result will be single pixel that is overall average or representative of the selected kernel size pixels.


<code>__2. Activation Layer:__</code> Reduced image size generated in convolution layer is the input to this layer. Activation function such as ReLu introduce non linearity to allow network to learn independent using backpropagation algorithm.


<code>__3. Pooling Layer:__</code> Pooling layer further reduced the size of image by focusing on important features of images. Again filter is passed over the results which achieved from previous layer and selects the number which is maximum among them, this is called max pooling. This layer actually allow network to learn faster by focusing on specific and important feature from image.

<code>__4. Fully Connected Layer:__</code> Here traditional neural network structure is present which can be multilayer perceptron. This is one dimensional vector represent the out from pooling layer passed as single input to hidden neurons. Whichever label receives the highest probability that will the classification decision.

We can add multiple convolution+activation, pooling layer in the CNN architecture.
