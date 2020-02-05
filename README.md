# Deep Learning Algorithms
Implementation of famous Deep Learning Algorithms in pytorch 

#### 1. Hello World of Deep Learning
Implemented a fully connected neural network to classify handwritten digits. 
Further explored which node in different layers are firing for different kinds of digits 

#### 2. Audio Denoising using Fully connected network completed
Implemented a fully connected neural network to learn mask to denoise audio having chip eating noise

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
Compared network performance with respect of number of parameters needed for the network to understand effect of network compression

#### 7. MNIST Generative Adversarial Network  
Implemented a generative adversarial network to generate handwritten digits similar to MNIST digits

#### 8. MNIST Conditional Generative Adversarial Network  
Implemented a conditional GAN to control which digit is generated.

#### 9. Siamese Network for Voice Identification
Implemented Siamese network to verify which audio clip belongs to which speaker.

#### 10. Varitional Autoencoder on MNIST
Learned the gaussian distribution which can generate MNIST digits.
Tried different combinations of parameters of the distribution to see effect on the generated digits.



