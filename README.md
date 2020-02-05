# Deep-Learning-Implementations
Implementation of few famous Deep Learning Algorithms in pytorch 

#### 1. Audio Denoising using Fully connected network completed
Implemented a fully connected neural network to learn mask to denoise audio having chip eating noise

#### 2. Hello World of Deep Learning Completed
Implemented a fully connected neural network to classify handwritten digits. 
Further explored which node in different layers are firing for different kinds of digits 

#### 3. Audio Denoising using 1D CNN implemented
Implemented a 1D convolutional neural network to learn mask to denoise audio having chip eating noise

#### 4. Audio Denoising using 2D CNN implemented
Implemented a 2D convolutional neural network to learn mask to denoise audio having chip eating noise
Suprisingly, 1D CNN outperforms 2D cnn. This can be reasoned by saying that audio data is kind of time series data 
and has only 2 dimentions, one is time and other is value at that time instance.
It makes more sense to use 2D convs for data with 3 dimentions. For example Images

#### 5. Audio Denoising using RNN implemented
Implemented a Recurrent neural network to learn mask to denoise audio having chip eating noise

#### 6. Network compression using SVD
Reduced network parameters by usage of SVD on the parameters. 
Comparison of network performance with respect of number of parameters needed for the network
