# VAE MNIST

This is a sample implementation by using Pytorch for Variational AutoEncoder.

## Variational AutoEncoder 
- Generative Modeling
  1. x1, ..., xn ~ D => Generate X1, X2, ..., Xn
  2. D might be a complex distribution (more so than a GMM)
- D is the distribution of HandWritten images number or imagenet (really complex) 
- Basically, mapping from a really complex distribution, D, to Gaussian distribution, then mapping from Gaussian distribution back to that complex distribution, D.
- It learns how to map the complex distributions to Gaussian distribution.
