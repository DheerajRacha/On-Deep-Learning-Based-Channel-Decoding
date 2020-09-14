[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ic8PGk17ZYAIIXhGRKjPs-UWHTQxYWjj)

# On-Deep-Learning-Based-Channel-Decoding
Tensorflow implementation of the paper ["On Deep Learning-Based Channel Decoding"](http://arxiv.org/abs/1701.07738)

![Neural Network Decoder](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FOn-deep-learning-based-channel-decoding-Gruber-Cammerer%2Ff3b944046602765fc1efc94264d291e4052a1a84&psig=AOvVaw1lRmbClYFEeDdyWnj6bivZ&ust=1600165319446000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOD477226OsCFQAAAAAdAAAAABAD)

This repository provides the complete code for the Keras (TensorFlow 2.2.0) implementation of the above paper with a brief report of the results and observations.

Google Colaboratory link is also provided for instantly start running the script!

The topics covered are:

- Implementation of a NND, Neural Network Decoder with custom layers ( BPSK Modulation and AWGN channel in the neural network model itself as proposed in the paper)
- Finding the optimal training SNR
- Experimental Investigation when the NND is trained at multiple SNR values**
- How many epochs for the NND to converge?
- Best Neural Netowrk architecture
- Capability of generalization
