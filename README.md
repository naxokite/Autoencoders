[//]: # (Image References)
[image1]: VAE_linspace_MNIST.png "linspace"
[image2]: VAE_faces_dense.png "faces"
[image3]: VAE_faces_conv.png "faces_conv"

# Autoencoders

Main goal of this repo is to try out different approaches to autoencoders to generate new samples. It is divided into 2 main categories with standalone jupyter notebooks:

![linspace][image1]

1. MNIST dataset:
  deep_autoencoder.ipynb: simple NN to encode the features with nor elation between encoder & decoder to test & prove empirically that random sampling in the feature space does not work
  VAE ULTRA.ipynb: Variational autoencoder on MNIST dataset to prove that sampling in the normally distributed feature space works
    
2. LFW dataset:
  VAE_ULTRA_LFW.ipynb: Variational autoencoder on LFW dataset & tensorflow to test VAEs in more complex features than MNIST
  
![faces][image2]
  
  VAE_ULTRA_LFW_CONV.ipynb: VAE with conv nets as encoder to see if it improves quality of results
   
![faces_conv][image3]
