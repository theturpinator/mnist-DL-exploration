This is a rework of Fast.ai's Deep Learning for Coder's tutorial in Chapter 4. In this Notebook, we explore:
1. The representation of images in computers
2. Creating a naive classifier by measuring the distance of each training instance from each "ideal" digit (i.e., the pixel-wise average of all training instances for that digit)
3. Manually creating a training loop to calculate the loss of our prediction, identify the gradients, and step the parameters in the right direction to minimize the loss function.
4. Using PyTorch and Fast.ai to build and train a Neural Network, acheiving 90%+ accuracy on the MNIST dataset
