# FastCycle-GAN
**DISCLAIMER:**
**THIS IS NOT YET A PRODUCTIVE MODEL, THE SOLUTION IS STILL IN DEVELOPMENT**
This is an on-going project repository for the implementation of an improved Cycle-GAN created by Jun-Yan Zhu et al, model using a Fast Fourier Transform (FFT) as a convolution layer. The model is proposed initially as a less time consuming solution to the Cycle-GAN approach given the Fast Fourier Transform implementation.

## Main Goal

Prove that the FFT implementation over the model gives as a result a more efficient result on the Unpaired Image to Image Translation problem, more specifically Image Colorization.

As a side goal to this project, it is expected to also add to the model a Spectral Pooling layer that is capable of extracting more features from the target images. This would come with the need to switch to another CNN Architecture different from the original publication of the Cycle-GAN model which used ResNet-like CNN architecture.

## About the project

This project is based on a thesis of a Master's Degree on Data Science for the CAECE University located in Buenos Aires, Argentina.
