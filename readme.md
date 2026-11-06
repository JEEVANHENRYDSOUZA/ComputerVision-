This repo contains the opencv2 way of performing convolution 
In modern learning in deep learning we dont need this as the feature engineering is automatically done by the model itself

the reason for performing convolution is we are trying to learn the features , because we are now using deep learning algorithms where feature engineering which has featuer engineering is automatically permfoed we are trying to understand how the back propogation algorithm will try to adjust the weights or in other words the values of the kernel  to perfomr convolution , intially we assign random values to the kernel filter matrix and then we will learn the values of the kernel matrix 


images are represnted as digital data hence we will be only focusing on discrete time domain 

convolution only works if the system is lti or linear time invarient 
   1. for linearity :  a. additivity 
                       b. homogenity
   2. time invarient : if there is a shift in input there is a corresponding change in the output