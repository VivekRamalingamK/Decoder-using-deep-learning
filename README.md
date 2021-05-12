# Decoder-using-deep-learning
Academic project for constructing the decoder for communication using Deep learning networks - CNN architecture and ResNet Inception model architecture.

Abstract:
The main shortcoming of the deep learning-based channel decoding is the curse of the dimensionality.
To overcome this shortcoming, the neural network must learn some form of
decoding algorithm. This learning is possible only for structured codes not random codes.
In this project work, attempt for construction of such decoder is done using convolutional
neural network (CNN) and residual network inception model. The illustration of decision of
hyperparameters for NN is explained and comparison of the CNN, residual neural network
inception model and the dense layer network is done. For higher values of message length in
the codeword, the performance of the CNN and residual network inception model decoders
are explained.

This project is based on the implementation of the published paper given in the following link https://arxiv.org/abs/1701.07738.

This project is guided by Dr.-Ing. Jakob Hoydis, Sebastian Dörner,Sebastian Cammerer, Prof. Stephan ten Brink from University of Stuttgart.

In the Jupyter notebooks, only the construction and the hyperparameter tuning of the deep learning models part was done by me, the rest were provided by the above mentioned guides.

References:

[1] Gruber, Tobias & Cammerer, Sebastian & Hoydis, Jakob & Brink, Stephan. (2017). On Deep Learning-Based Channel Decoding. url: http://arxiv.org/abs/1701.07738

[2] https://github.com/gruberto/DL-ChannelDecoding
