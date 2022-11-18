# AutoEncoders
# Basic AutoEncoders
Autoencoders (AE) are neural networks that aims to copy their inputs to their outputs. They work by compressing the input into a latent-space representation, and then reconstructing the output from this representation. This kind of network is composed of two parts :

Encoder: This is the part of the network that compresses the input into a latent-space representation. It can be represented by an encoding function h=f(x).
Decoder: This part aims to reconstruct the input from the latent space representation. It can be represented by a decoding function r=g(h).

implementation of various autoencoder

# [Linear autoencoder](linear_autoencoder)
# [simple autoencoder](simple_autoencoder)
# [Deep Auroencoder](deep_autoencoder)
# [Denoising auroencoder](denoising_autoencoder)
# [Variation autoencoder](variational_autoencoders)
This is a variation of autoencoder which is generative model.
The main difference of variational autoencoder with regular autoencoder is that the encoder output is a mean vector and variance vector.
Then it is used to generate latent vector which is passed to Decoder network
