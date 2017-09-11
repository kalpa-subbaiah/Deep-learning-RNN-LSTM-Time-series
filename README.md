# CNN-Assignment


1.	Convolution Neural Network

i.	Import the cifar10 dataset from keras.datasets.

ii.	Normalize the data from 0-255 to 0.0-1.0.

iii.	One-hot encode the target variable.

iv.	Build the following CNN Architecture:

a)	Convolutional input layer, 32 feature maps with a size of 3×3, a rectifier activation function and a weight constraint of max norm set to 3.

b)	Dropout set to 20%.

c)	Convolutional layer, 32 feature maps with a size of 3×3, a rectifier activation function and a weight constraint of max norm set to 3.

d)	Max Pool layer with size 2×2.

e)	Flatten layer.

f)	Fully connected layer with 512 units and a rectifier activation function.

g)	Dropout set to 50%.

h)	Fully connected output layer with 10 units and a softmax activation function.

v.	Run the model for 2 epochs and print the accuracy.


## *Nb: You are required to submit both Rmd file and HTML/PDF*

